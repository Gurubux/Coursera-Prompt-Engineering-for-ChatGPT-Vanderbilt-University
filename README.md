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

# Module 3 : Prompts Patterns I
## 3.1 Question Refinement Pattern
### **Transcript Summary: Question Refinement Pattern**  

#### **What Is the Question Refinement Pattern?**  
- A **simple yet powerful technique** to improve interactions with LLMs like ChatGPT.  
- The **goal** is to **enhance the clarity, specificity, and effectiveness** of questions by letting the AI suggest improvements.  
- **Why?** AI is trained on vast amounts of data and **recognizes common patterns** that make questions more precise and informative.  

#### **How the Pattern Works**  
- Instead of asking a vague or general question, **we instruct the AI to refine it** before answering.  
- **Basic prompt format:**  
  - _"Whenever I ask a question, suggest a better question and ask me if I would like to use it instead."_  
- **Improved version:**  
  - _"Whenever I ask a question, suggest a better version. If I say yes, use the refined question; if I say no, answer the original one."_  
- This small tweak **eliminates the need for manual copying and pasting** and makes interactions more seamless.  

#### **Example: Should I Go to Vanderbilt University?**  
1. **User's Original Question:**  
   - _“Should I go to Vanderbilt University?”_  
   - **Issue:** Too vague—lacks personal context, criteria, or decision factors.  
2. **AI’s Refined Question Suggestion:**  
   - _“What factors should I consider when deciding whether or not to attend Vanderbilt University, and how do they align with my personal goals and priorities?”_  
   - **Why it’s better:**  
     - Adds **decision criteria** (factors to consider).  
     - Encourages **self-reflection** (alignment with goals).  
     - **Clarifies the intent** of the question.  
3. **User’s Options:**  
   - **Say “Yes”** → AI proceeds with the refined question.  
   - **Say “No”** → AI answers the original question.  

#### **Why This Pattern Is Useful**  
- **Improves question quality** → leads to **more useful and precise AI responses**.  
- **Reveals missing context** → Helps users identify **what additional details** should be included.  
- **Encourages self-reflection** → Users can **reframe their own thoughts and priorities**.  
- **Reduces ambiguity** → Ensures that **AI doesn’t misinterpret vague or broad questions**.  

#### **Key Takeaways**  
- The **Question Refinement Pattern helps users craft clearer, more meaningful queries.**  
- **LLMs can assist in improving questions**, leading to **better insights and responses**.  
- **This technique is useful across multiple domains**, from decision-making to research and problem-solving.  
- **Refining questions iteratively improves conversations**, making AI interactions more productive and insightful.
## 3.2 Format of the Question Refinement Pattern
#### **Fundamental Contextual Statements for the Pattern**  
To apply the **Question Refinement Pattern**, your prompt should include the following instructions:  
1. **Core Instruction:**  
   - _"From now on, whenever I ask a question, suggest a better version of the question to use instead."_  
2. **Optional Enhancement:**  
   - _"Ask me if I would like to use the better version instead before proceeding."_  

#### **General Examples of the Pattern**  
1. _"From now on, whenever I ask a question, suggest a better version of the question to use instead."_  
2. _"From now on, whenever I ask a question, suggest a better version of the question and ask me if I would like to use it instead."_  

#### **Tailored Examples for Specific Contexts**  
1. **Diet & Nutrition Focus:**  
   - _"Whenever I ask a question about dieting, suggest a better version of the question that emphasizes healthy eating habits and sound nutrition. Ask me for the first question to refine."_  
2. **Sports Debate (GOAT Discussions):**  
   - _"Whenever I ask a question about who is the greatest of all time (GOAT), suggest a better version of the question that puts multiple players’ unique accomplishments into perspective. Ask me for the first question to refine."_  

#### **Key Takeaways**  
- **The pattern enhances clarity, precision, and usefulness of AI-generated responses.**  
- **It helps users refine their own thoughts**, leading to **more thoughtful and well-structured queries.**  
- **Customizing refinements to specific topics** (e.g., dieting, sports, career decisions) **ensures better alignment with user goals.**  
- **Adding the option for confirmation** allows users to **choose between their original question and the refined version, giving them greater control.**  

By **structuring prompts with this pattern**, AI-assisted conversations **become more insightful, personalized, and valuable.** 🚀
## 3.3 Cognitive Verifier Pattern
### **Transcript Summary: Cognitive Verifier Pattern**  

#### **What Is the Cognitive Verifier Pattern?**  
- A **technique that improves reasoning in LLMs** by breaking a problem into **smaller, more manageable subproblems**.  
- This **mirrors human problem-solving**, where breaking down a complex issue helps in reaching a **logical, well-structured answer**.  
- **Key Insight:** LLMs **recognize patterns in problem-solving steps** and often perform better when they **explicitly reason through subproblems**.  

#### **How the Pattern Works**  
1. **Break the primary question into several related subquestions.**  
2. **Answer each subquestion separately** to build a **context-rich foundation**.  
3. **Combine individual answers** to form the **final response** to the main question.  
4. **Improve user understanding** by surfacing **missing dimensions or key factors** in the reasoning process.  

#### **Example: Estimating Mosquitoes in a Front Yard**  
1. **User’s Question:**  
   - _“How many mosquitoes probably live in my front yard?”_  
2. **AI Applies the Cognitive Verifier Pattern** by generating subquestions:  
   - _“What is the size of your front yard?”_  
   - _“What is the climate like in your area?”_  
   - _“What time of year is it?”_  
   - _“Are there any bodies of standing water nearby?”_  
   - _“Are there any plants or vegetation mosquitoes are attracted to?”_  
3. **User Provides Answers:**  
   - _Front yard: ~2,500 sq ft._  
   - _Location: Southeastern U.S._  
   - _Season: April._  
   - _No standing water._  
   - _Some vegetation present._  
4. **AI’s Final Estimate:**  
   - Predicts **a few dozen to a few hundred mosquitoes**, adjusting for factors like **climate, seasonality, and breeding conditions**.  

#### **Why This Pattern Works Well**  
- **Improves accuracy** → Instead of a generic response, the AI considers **specific influencing factors**.  
- **Encourages structured reasoning** → AI explains **why** it is arriving at a particular conclusion.  
- **Reduces skepticism** → Users trust responses more when they **see the step-by-step breakdown**.  
- **Guides users to missing details** → If key information is omitted, the AI **helps refine the question**.  

#### **Key Takeaways**  
- **The Cognitive Verifier Pattern enhances AI reasoning by breaking down problems into logical subquestions.**  
- **It enables more nuanced, well-reasoned responses** instead of vague or overly general answers.  
- **Users gain better insights** by understanding how different factors **interconnect to shape the final answer**.  
- **This method is valuable across multiple domains**, from **scientific reasoning** to **business decision-making**.  

By **integrating this pattern into AI conversations**, users can **achieve greater accuracy, depth, and trust in AI-generated answers**. 🚀
## 3.4 Format of the Cognitive Verifier Pattern
#### **Fundamental Contextual Statements for the Pattern**  
To apply the **Cognitive Verifier Pattern**, your prompt should include the following instructions:  
1. **Define the process:**  
   - _“When you are asked a question, follow these rules.”_  
2. **Break the question into subquestions:**  
   - _“Generate a number of additional questions that would help more accurately answer the question.”_  
3. **Synthesize answers into a final response:**  
   - _“Combine the answers to the individual questions to produce the final answer to the overall question.”_  

#### **General Example of the Pattern**  
- _"When you are asked a question, follow these rules: Generate a number of additional questions that would help you more accurately answer the question. Combine the answers to these questions to produce the final answer."_  

#### **Tailored Examples for Specific Use Cases**  
1. **Cooking & Recipes:**  
   - _"When you are asked to create a recipe, follow these rules: Generate a number of additional questions about the ingredients I have on hand and the cooking equipment that I own. Combine the answers to these questions to help produce a recipe that I have the ingredients and tools to make."_  

2. **Travel Planning:**  
   - _"When you are asked to plan a trip, follow these rules: Generate a number of additional questions about my budget, preferred activities, and whether or not I will have a car. Combine the answers to these questions to better plan my itinerary."_  

## 3.5 Audience Persona Pattern
#### **What Is the Audience Persona Pattern?**  
- A **variation of the Persona Pattern**, but instead of telling the LLM **who it should act as**, we tell it **who the audience is**.  
- The LLM then **tailors its response to match the audience's background, knowledge level, and preferences**.  
- **Why?** Instead of manually defining rules for how to format the response, **we simply describe the audience**, and the model **adapts its explanation accordingly**.  

#### **How the Pattern Works**  
1. **User provides a question or topic** (e.g., "Explain large language models and how they work.")  
2. **User specifies an audience persona** (e.g., "Assume I have no background in computer science.")  
3. **The AI customizes the response** based on what it knows about that persona.  

#### **Examples of the Pattern in Action**  

1. **Explaining LLMs to a General Audience**  
   - **Prompt:** _"Explain large language models to me. Assume I have no background in computer science."_  
   - **AI Output:**  
     - Uses **simple language**: _"A large language model is a type of computer program that understands and generates human language."_  
     - Avoids **technical jargon**.  
     - Provides **real-world applications** (e.g., chatbots, translation, speech recognition).  
   
2. **Explaining LLMs to Christopher Columbus**  
   - **Prompt:** _"Explain large language models to me. Assume I am Christopher Columbus."_  
   - **AI Output:**  
     - Adapts to **historical knowledge**: _"Imagine a magical scribe who has read countless scrolls and manuscripts from around the world."_  
     - Uses **familiar metaphors** instead of modern computing terms.  

3. **Explaining LLMs to a Second Grader Who Gets Bored Easily**  
   - **Prompt:** _"Explain large language models to me. Assume I am a second grader who gets bored easily."_  
   - **AI Output:**  
     - Uses **engaging, playful language**: _"Imagine a robot friend who loves playing word games and telling stories!"_  
     - Breaks down concepts into **short, fun sections**.  
     - Keeps the explanation **lively and interactive**.  

4. **Explaining LLMs Using Only Math**  
   - **Prompt:** _"Explain large language models to me. Assume I only accept explanations in math."_  
   - **AI Output:**  
     - Defines LLMs as **probability distributions**.  
     - Uses **equations and statistical models** to describe token prediction.  

#### **Why the Audience Persona Pattern Is Powerful**  
- **Simplifies prompt engineering**—users don’t have to explicitly define formatting rules.  
- **Encourages AI to use contextually appropriate explanations** based on audience needs.  
- **Generates highly customized, relevant, and engaging responses** across different knowledge levels.  
- **Expands creative AI applications**, such as storytelling, teaching, or business communication.  

#### **Key Takeaways**  
- The **Audience Persona Pattern** is **a powerful way to guide AI responses** by defining **who the content is for**.  
- **AI adapts naturally** to different audiences, **making complex topics more accessible or specialized**.  
- **Combining this with the Persona Pattern** can create **richer, highly contextual AI interactions**.  

By **leveraging this pattern**, users can **generate highly engaging, audience-specific content with minimal effort**. 🚀
## 3.6 Format of the Audience Persona Pattern
To use this pattern, your prompt should make the following fundamental contextual statements:  

**Explain X to me.**  

**Assume that I am Persona Y.**  

You will need to replace **"Y"** with an appropriate persona, such as **"have limited background in computer science"** or **"a healthcare expert"**. You will then need to specify the topic **X** that should be explained.  

### **Examples:**  

- **Explain large language models to me. Assume that I am a bird.**  
- **Explain how the supply chains for US grocery stores work to me. Assume that I am Genghis Khan.**  

## 3.7 Flipped Interaction Pattern
#### **What Is the Flipped Interaction Pattern?**  
- A technique where **the AI asks the user questions instead of answering them**.  
- Useful for **problem-solving, guided decision-making, and interactive experiences**.  
- Particularly valuable when **users lack knowledge on what information is needed** to reach a goal.  

#### **How the Pattern Works**  
1. **User defines a topic and a goal** → AI generates **relevant questions**.  
2. **AI asks questions one at a time** (or in batches) until it gathers enough information.  
3. **Once enough details are collected, AI produces the final output.**  

#### **Example: AI Designing a Strength Training Regimen**  

1. **User Input (Setting Up the Pattern)**  
   - _"Ask me questions about fitness goals until you have enough information to suggest a strength training regimen for me. When you have enough information, show me the strength training regimen. Ask me the first question."_  

2. **AI Starts Asking Questions:**  
   - _“What are your specific fitness goals? Are you looking to build muscle mass, increase strength, endurance, or achieve a particular goal?”_  
   - _“Do you have any current or past medical conditions or injuries?”_  
   - _“How many days per week can you dedicate to training?”_  
   - _“Do you have access to a gym or fitness equipment?”_  

3. **User Provides Answers**  
   - _Goal: Build explosive power and prevent knee pain from mountain biking._  
   - _Medical Concern: Possible patellar tendonopathy._  
   - _Schedule: 5 days per week, 30-45 minutes per session._  
   - _Equipment: Access to gym weights._  

4. **AI Generates a Customized Training Plan**  
   - **Exercises tailored to explosive power** (e.g., goblet squats, split squats).  
   - **Includes knee-friendly strengthening routines** for injury prevention.  
   - **Structured weekly workout plan** based on available time and equipment.  

#### **Why This Pattern Works Well**  
- **Removes user guesswork** → AI **asks the right questions**, ensuring **all necessary details are collected**.  
- **Improves AI-generated output** → Instead of **generic responses**, AI produces **tailored results** based on the user’s actual needs.  
- **Mimics real-world consultation** → Similar to **a personal trainer, doctor, or customer support agent** gathering information before making recommendations.  
- **Enhances interactivity** → Can be used for **quizzes, guided troubleshooting, and interactive learning.**  

#### **Applications of the Flipped Interaction Pattern**  
- **Fitness Coaching:** AI gathers user details before generating a workout plan.  
- **Customer Support:** AI asks diagnostic questions before suggesting a solution.  
- **Career Guidance:** AI collects skills and interests before recommending jobs.  
- **Educational Quizzes:** AI generates questions to test or reinforce learning.  
- **Game Design:** AI leads interactive storytelling or puzzle-solving experiences.  

#### **Key Takeaways**  
- **The Flipped Interaction Pattern transforms AI from a passive responder to an active guide.**  
- **It ensures better responses by prompting users for critical information before generating output.**  
- **It can be used for a wide range of applications**, from personal coaching to automated customer service.  

By **reversing the typical AI interaction flow**, this pattern **creates more engaging, dynamic, and useful AI-driven experiences**. 🚀
## 3.8 Format of the Flipped Interaction Pattern
To use this pattern, your prompt should make the following fundamental contextual statements:  

- **I would like you to ask me questions to achieve X.**  
- **You should ask questions until condition Y is met or to achieve this goal (alternatively, forever).**  
- _(Optional)_ **Ask me the questions one at a time, two at a time, ask me the first question, etc.**  

You will need to replace **"X"** with an appropriate goal, such as **"creating a meal plan"** or **"creating variations of my marketing materials."**  
You should specify when to stop asking questions with **"Y."** Examples: **"until you have sufficient information about my audience and goals"** or **"until you know what I like to eat and my caloric targets."**  

### **Examples:**  

- **I would like you to ask me questions to help me create variations of my marketing materials.** You should ask questions **until you have sufficient information about my current draft messages, audience, and goals.** Ask me the first question.  

- **I would like you to ask me questions to help me diagnose a problem with my Internet.** Ask me questions **until you have enough information to identify the two most likely causes.** Ask me **one question at a time.** Ask me the first question.  

## 3.9 Applying Prompt Patterns I

# Module 4 Few-shot Examples
## 4.1 Few-shot Examples
#### **What Are Few-shot Examples?**  
- **A technique for teaching LLMs patterns using examples** instead of explicit instructions.  
- Instead of saying _“Analyze these reviews and determine if they are positive, neutral, or negative,”_ we **show** the AI **examples of inputs and their correct outputs**.  
- This **guides the AI** to **predict the correct pattern** based on the given examples.  

#### **How the Pattern Works**  
1. **Provide multiple labeled examples** of the input-output format you want the AI to follow.  
2. **Present a new input** and prompt the AI to complete it using the learned pattern.  
3. **The AI predicts the expected output** by following the structure of the previous examples.  

#### **Example: Sentiment Analysis Using Few-shot Prompting**  
We train the AI to classify sentiments based on a set of **few-shot examples**:  

**Prompt with Examples:**  
```
Input: The movie was good but a bit long.  
Sentiment: Neutral  

Input: I didn't really like this book, it lacked important details and didn’t end up making sense.  
Sentiment: Negative  

Input: I love this book! It was really helpful in learning how to improve my gut health.  
Sentiment: Positive  

Input: I wasn’t sure what to think of this new restaurant. The service was slow, but the dishes were pretty good.  
Sentiment:  
```
**AI Output:** _Neutral_  

#### **Why This Works Well**  
- **AI identifies the pattern**—each input has a **matching sentiment label** (Positive, Neutral, or Negative).  
- **It follows the label format** without being explicitly told what "Neutral" means.  
- **Prediction is guided by example structure**—AI **expects "Sentiment:" as the next word**.  

#### **Testing Generalization: New Input Without a Label**  
If we provide:  
```
Input: I really hated this coffee, it was roasted too much and tasted burned.  
```
**AI Output:**  
```
Sentiment: Negative  
```
- AI **predicts the correct category** without needing explicit instruction.  
- It **generalizes from previous examples** and **applies learned patterns to new data**.  

#### **Key Takeaways**  
- **Few-shot prompting helps AI learn by example** instead of rule-based instructions.  
- **It works well for structured tasks** like **classification, formatting, and structured data extraction**.  
- **AI follows patterns naturally** by recognizing word associations and relationships in the given examples.  
- **This technique is useful for NLP tasks**, such as **translation, text summarization, and data labeling**.  

By **leveraging few-shot examples**, users can **effectively guide AI behavior** without needing **extensive instructions**. 🚀
## 4.2 Few-shot Examples for Actions
### **Transcript Summary: Few-shot Examples for Actions**  

#### **Few-shot Examples for Decision-making and Planning**  
- **Few-shot prompting isn't limited to classification tasks**—it can be used for **decision-making and planning**.  
- AI can **learn patterns from a few examples** and **predict appropriate next actions** in various situations.  
- Instead of explicitly instructing the model on how to make decisions, **we show examples of inputs (situations) and their corresponding outputs (actions)**.  

#### **Example: Driving Situations and Actions**  

**Few-shot Prompt for Driving Decisions:**  
```
Situation: I'm traveling 60 miles per hour and I see the brake lights on the car in front of me come on.  
Action: Brake.  

Situation: I've just entered the highway from an on-ramp and I'm traveling 30 miles per hour.  
Action: Accelerate.  

Situation: A deer has darted out in front of my car while I'm traveling 15 miles per hour and the road has a large shoulder.  
Action: Brake and swerve into the shoulder.  

Situation: I'm backing out of a parking spot and I see the reverse lights illuminate on the car behind me.  
Action:  
```
**AI Completes the Pattern:**  
```
Stop and wait for the car to back out before proceeding.
```
- The AI **predicts the expected response** based on previous patterns.  
- **It generalizes from prior examples** and **makes reasonable driving decisions**.  

#### **Generating More Examples with AI**  
- **Prompt:** _“Please provide more examples.”_  
- AI **generates additional driving situations and actions**, such as:  
  - _“You are driving in heavy rain and notice that the road ahead is flooded.” → **Action: Slow down and cautiously drive through the flooded area.”_  
  - _“You are driving on a two-lane road and a car is approaching you with high beams on.” → **Action: Dim your headlights to avoid blinding the driver.”_  

⚠ **Issue:** AI **sometimes provides incorrect or unsafe advice** (e.g., driving through flooded areas).  
- **Human intervention is needed** to **verify, correct, or discard bad responses.**  

#### **Applications of Few-shot Prompting for Actions**  
1. **Self-driving cars (hypothetically)** → Teaching AI how to **react to road conditions.**  
2. **Emergency response training** → AI predicts **first-aid or survival actions** in different crises.  
3. **Customer service automation** → AI follows **decision trees based on customer inquiries.**  
4. **Game AI behavior** → AI predicts **NPC (non-playable character) reactions** in video games.  
5. **AI-assisted coaching** → AI recommends **sports or fitness adjustments** based on situational inputs.  

#### **Key Takeaways**  
- **Few-shot prompting works beyond text classification—it can be used for dynamic decision-making.**  
- **AI can be trained to generate actions in different contexts**, making it a powerful tool for **simulation, training, and automated decision-making.**  
- **AI-generated examples can be curated by humans and used to improve AI models.**  
- **AI output should always be validated**—it may **generate unsafe or impractical suggestions**.  

By **leveraging few-shot examples for decision-making**, AI can be **taught to predict intelligent responses in complex situations.** 🚀
## 4.3 Few-Shot Examples with Intermediate Steps
#### **Expanding Few-shot Examples with Step-by-step Reasoning**  
- **Few-shot prompting isn’t limited to just input-output pairs.**  
- By introducing **intermediate steps**, LLMs can learn **multi-step reasoning and decision-making**.  
- This **helps the AI model break down problems** logically and **simulate sequential actions**.  

#### **Example: Driving Situations with Multi-step Actions**  

##### **Basic Few-shot Example (From Before)**  
```
Situation: I'm traveling 60 miles per hour and I see the brake lights on the car in front of me come on.  
Action: Brake.  
```
- This **directly maps an input (situation) to an output (single action).**  
- But **real-world decisions require multiple steps.**  

##### **Enhanced Example with Intermediate Steps:**  
```
Situation: I'm traveling 60 miles per hour and I see the brake lights on the car in front of me come on.  

Think: I need to slow the car down before I hit the car in front of me.  
Action: Press foot on brake.  

Think: The car isn't going to stop in time.  
Action: Check if the shoulder is wide enough to swerve into.  

Think: The shoulder is wide enough.  
Action: Swerve into the shoulder.  
```
- The AI **now thinks through the steps needed to avoid an accident**.  
- Instead of **one action**, it **evaluates options step-by-step before making decisions**.  

#### **Another Example: Merging onto a Highway**  
```
Situation: I've just entered the highway from an on-ramp and I'm traveling at 30 miles per hour.  

Think: I need to speed up to the speed limit so that I don’t get hit from behind.  
Action: Press foot on accelerator.  

Think: I’ve reached the speed limit.  
Action: Let up on the accelerator.  
```
- This **models gradual decision-making**, ensuring **actions align with real-world behavior**.  

#### **Testing AI with an Unfinished Example**  
```
Situation: I'm backing out of a parking spot and I see the reverse lights illuminate on the car behind me.  

Action:  
```
- **AI Completes the Pattern:**  
```
Action: Immediately stop backing up.  

Think: I need to check my surroundings to make sure it's safe to continue backing up.  
Action: Check mirrors and surroundings for any obstacles or pedestrians.  

Think: It is safe to continue backing up.  
Action: Continue backing up slowly and carefully while keeping an eye on surroundings.  
```
- AI **follows the example format**, structuring **decisions in a step-by-step process.**  
- **Instead of stopping at a single action, it evaluates what to do next.**  

#### **Generating Additional Examples Automatically**  
- The model can **generate new situations and step-by-step decisions** by following the learned pattern:  
```
Situation: I’m driving on a narrow winding road with several blind curves.  

Think: I need to slow down and be cautious to avoid any potential collisions.  
Action: Reduce speed and remain alert.  

Think: Visibility is limited due to sharp turns.  
Action: Use headlights and hug the centerline cautiously.  

Think: The road ahead is clear.  
Action: Resume normal speed.  
```
- AI **now generates its own step-by-step reasoning** using the learned structure.  

#### **Key Takeaways**  
- **Few-shot examples with intermediate steps enable AI to simulate complex decision-making.**  
- **This approach is useful for:**  
  - **Customer service** (troubleshooting step-by-step).  
  - **Emergency response** (handling accidents logically).  
  - **Education and training** (guiding learners through multi-step tasks).  
- **AI can generate new examples based on learned patterns**, making it a **powerful tool for process modeling.**  

By **teaching AI to think in steps, we create more sophisticated, structured reasoning models.** 🚀
## 4.4 Writing Effective Few-Shot Examples
#### **Common Mistakes in Few-Shot Prompting**  
- **Lack of clear formatting and context in the examples.**  
- **Unclear or overly generic prefixes** (e.g., using "Input" and "Output" without specifying the task).  
- **Examples that are too vague**, leading the AI to misinterpret the task.  
- **Not enough examples**, making it difficult for the AI to infer the correct pattern.  
- **Inconsistent or incomplete information in input data**, making classification unclear.  

#### **Example of a Bad Few-shot Prompt**  
```
Input: Brick  
Output: Hard  

Input: Pillow  
Output: Soft  

Input: Car  
```
🔴 **Problem:**  
- AI **doesn’t have enough context** to infer what to output for "Car."  
- **Are we asking about texture, density, or another property?**  
- AI **predicts "Fast" or "Transportation"**, which shows it didn’t recognize the hardness classification task.  

#### **Fixing the Few-shot Prompt with More Clarity**  
```
Task: Classify objects based on their surface feel. The output can only be "Soft" or "Hard."  

Example 1:  
Object: Brick  
Surface Feel: Hard  

Example 2:  
Object: Pillow  
Surface Feel: Soft  

Example 3:  
Object: Car  
Surface Feel:  
```
✅ **Improvements:**  
- **Added task description** at the top to clarify the classification criteria.  
- **Explicitly defined output options ("Soft" or "Hard").**  
- **Kept examples consistent in structure.**  
- **Ensured each input has enough context** for the AI to correctly infer a pattern.  

---

#### **Example of Vague Inputs Leading to Ambiguous AI Responses**  
```
Object: Plane  
Speed: Fast  

Object: Worm  
Speed: Slow  

Object: Ball  
Speed:  
```
🔴 **Problem:**  
- AI **responds with "Variable"**, because a ball **can be both fast or slow** depending on the context.  

#### **Fixing the Issue by Adding More Context**  
```
Object: Plane in flight  
Speed: Fast  

Object: Worm crawling  
Speed: Slow  

Object: Ball kicked by a baby  
Speed: Slow  
```
✅ **Improvements:**  
- **Added contextual details** to each object to clarify its typical speed.  
- **Ensured input examples reflect clear, real-world scenarios.**  
- **Provided enough information so that AI can confidently categorize new inputs.**  

---

### **Key Takeaways for Writing Effective Few-shot Examples**  

✅ **1. Use Descriptive Prefixes**  
- Instead of generic labels like **"Input" and "Output"**, use **specific ones like "Object: X, Surface Feel: Y"**.  
- This **helps AI understand what attributes are being classified.**  

✅ **2. Provide Context Before Examples**  
- **State the task explicitly** at the beginning of the prompt.  
- Example: _"Classify objects based on their surface feel. Choose 'Soft' or 'Hard'."_  

✅ **3. Ensure Sufficient and Relevant Examples**  
- **Cover a diverse range of cases** so AI can learn a reliable pattern.  
- **Avoid ambiguous inputs** (e.g., "Ball" alone is unclear, but "Ball kicked by a baby" provides clarity).  

✅ **4. Ensure AI Has Enough Data to Infer the Process**  
- If human readers might **struggle to guess the task**, **AI will struggle too.**  
- Make sure **each input contains enough information to determine the correct output.**  

✅ **5. Choose Between Explicit Instructions vs. Learning by Example**  
- **If a rule is simple, state it in text.**  
- **If a task is more complex, show it with multiple examples.**  
- Example: Instead of repeating "**Only respond with 'Soft' or 'Hard'**" in every example, say it once at the start.  

By **designing clear and structured few-shot examples**, AI models **perform better at classification, reasoning, and decision-making tasks.** 🚀
## 4.5 Chain of Thought Prompting
### **Transcript Summary: Chain of Thought Prompting**  

#### **What Is Chain of Thought (CoT) Prompting?**  
- A **prompting technique that improves AI reasoning by requiring it to "show its work."**  
- Instead of asking the model to **immediately provide an answer**, we **ask it to break down its reasoning step by step before answering.**  
- **Why does this help?**  
  - **Breaking down a problem into steps increases accuracy.**  
  - **If the reasoning is correct, the final answer is more likely to be correct.**  
  - **AI aligns its response with logical structures from its training data.**  

---

#### **Example: Without Chain of Thought Prompting**  
**Prompt:**  
```
Question: I am in a spaceship without gravity. I have a cup with a needle in it. I move my foot on the bed, knocking over the cup onto the floor. I lift a book up and put it on a desk. Is there anything on the floor?  
```
**AI's Response (Without CoT):**  
```
Yes. When the cup with a needle in it is knocked over onto the floor, both the cup and the needle will end up on the floor.
```
**Problem:**  
- **AI applies Earth-based logic**, assuming the objects will fall.  
- **Fails to account for zero-gravity conditions.**  

---

#### **Example: With Chain of Thought Prompting**  
**Revised Prompt with Step-by-step Reasoning:**  
```
Question: I am in a spaceship without gravity. I have a cup with a needle in it. I move my foot on the bed, knocking over the cup onto the floor. I lift a book up and put it on a desk.  

Reasoning:  
- In a spaceship without gravity, objects do not fall as they do on Earth.  
- Instead, objects move in the direction of the force applied to them and float until stopped.  
- When I knock over the cup, it does not fall to the floor but instead drifts in the direction of the applied force.  
- There is no concept of "on the floor" in zero gravity, as objects do not settle due to gravity.  

Answer: No.  
```
**AI's Response (With CoT):**  
```
No. In a spaceship without gravity, objects do not fall onto the floor. Instead, they will float in the direction of the force applied and remain suspended.
```
**Why This Answer Is Better:**  
- **AI correctly considers zero-gravity physics.**  
- **Instead of making an immediate assumption, it follows a logical reasoning process before answering.**  

---

#### **Comparing AI Performance: Without vs. With Chain of Thought**  
| **Scenario**                 | **Without CoT** (Immediate Answer) | **With CoT** (Step-by-Step Reasoning) |
|------------------------------|----------------------------------|-----------------------------------|
| **Math Problem**             | Produces incorrect answer        | Breaks down calculations and improves accuracy |
| **Physics Question**         | Applies Earth-based logic       | Considers external conditions (e.g., gravity) |
| **Logic Puzzle**             | Jumps to conclusion             | Analyzes different conditions before answering |
| **Complex Reasoning**        | May be inconsistent             | Produces well-structured responses |

---

#### **How Chain of Thought Prompting Works in Few-shot Learning**  
When using **few-shot examples**, we **explicitly teach the AI** how to apply **step-by-step reasoning** before providing an answer.  

**Example of Few-shot CoT Prompting for Math Reasoning:**  
```
Question: Four bike racers start a race and travel an average of 30 miles per hour. They each race for two hours. Is the total number of miles ridden by all riders greater than 200?  

Reasoning:  
- Each racer travels 30 mph × 2 hours = 60 miles.  
- There are 4 racers, so total distance = 4 × 60 miles = 240 miles.  
- Since 240 miles > 200 miles, the answer is yes.  

Answer: Yes.  
```
✅ **AI learns that before answering, it must explain calculations.**  

---
```
Q: "Question example 1"
A: Reasoining - "Specifiy Reasoning example 1"
Answer - YES

Q: "Question example 2"
A: Reasoining - "Specifiy Reasoning example 2"
Answer - NO

Q: "Actual Question"
A: Reasoning - <REASOINING> Answer - <ANSWER>
```

#### **Key Takeaways: Why Use Chain of Thought Prompting?**  
✅ **1. Improves Accuracy:** AI **avoids mistakes by breaking complex tasks into logical steps.**  
✅ **2. Encourages Logical Flow:** AI **follows structured reasoning, making responses more reliable.**  
✅ **3. Helps Explainable AI (XAI):** AI **becomes more interpretable and transparent** in decision-making.  
✅ **4. Works for Various Domains:** Useful for **math, physics, logic puzzles, and complex decision-making.**  

By **implementing Chain of Thought Prompting**, we enable AI to **think before answering**, resulting in **higher accuracy and better reasoning.** 🚀
## 4.6 Learn More About Chain of Thought Prompting
You can learn more about **Chain of Thought Prompting** by reading the research paper:  

📄 **"Chain-of-Thought Prompting Elicits Reasoning in Large Language Models"**  
**Authors:** Jason Wei, Xuezhi Wang, Dale Schuurmans, Maarten Bosma, Brian Ichter, Fei Xia, Ed Chi, Quoc Le, Denny Zhou  

🔗 **Link to Paper:** [https://arxiv.org/abs/2201.11903](https://arxiv.org/abs/2201.11903)  

This paper explores how **step-by-step reasoning improves performance** in large language models across various tasks, particularly in **math, logic, and complex reasoning problems.** 🚀
## 4.7 ReAct Prompting
### **Transcript Summary: ReAct Prompting**  

#### **What Is ReAct Prompting?**  
- **ReAct** stands for **Reasoning + Acting**—it allows an AI to **think through a problem step-by-step and take external actions** (e.g., searching the web, using a calculator, or querying APIs).  
- **Why use ReAct?** Large Language Models **lack real-time access to external data**, so **they need to call external tools to retrieve new information**.  
- ReAct is an **expansion of Chain of Thought (CoT) prompting**, where AI not only explains its reasoning but **identifies when it needs external help**.  

---

#### **Example Task: Finding BMX Race Arrival Time**  
The goal is to **calculate when a racer needs to arrive at a BMX event for a 9:00–10:00 race**. Since AI **doesn't know** the race schedule, it must **query an external website**.  

##### **Step 1: Teaching AI How to Think and Use External Tools**  
We **manually provide a worked example** where AI reasons through the problem and **calls external sources** when needed:  
```
Task: Calculate when I need to arrive at the Music City BMX national race for my son to be on time for his 9:00-10:00 open race.  

Think: I need to find out what time the first race begins.  
I can use a web search of the Music City BMX site to get that information.  

Action: Search [musiccitybmx.com/schedule]  

Result: All races start at 9:00 AM.  

Think: I need to find out how many motos run before the 9:00-10:00 open race.  
I can use a web search of Music City BMX site to get that information.  

Action: Search [musiccitybmx.com/motos]  

Result: There are 30 motos before the 9:00-10:00 open race.  

Think: I need to find out how long each moto took last year.  
I can use the video live stream from the USA BMX website to measure the time.  

Action: Video [usabmx.com/live]  

Result: The first 10 motos took 5 minutes.  

Think: If 10 motos took 5 minutes, then 30 motos will take 15 minutes.  
The race starts at 9:00 AM, so I need to arrive before 9:15 AM.  
I will arrive 30 minutes early at 8:45 AM to be safe.  
```
- This example **teaches the AI**:
  - How to **break the problem into steps**.  
  - When to **call external sources (Search, Video, etc.)**.  
  - How to **incorporate results into reasoning**.  

---

##### **Step 2: AI Uses the Learned Pattern to Solve a New Problem**  
Now, we give the AI a **new task**:  
```
Task: Calculate what time my 36-40 novice race will end at the USA BMX Grand Nationals.  

Think:  
```
**AI Response (Using ReAct Thinking):**  
```
Think: I need to find out what time the first race begins at the USA BMX Grand Nationals.  
I can use a web search of the USA BMX site to get the information.  

Action: Search [usabmx.com/grands/schedule]  

Result: The first race begins at 8:00 AM.  

Think: I need to find out how many motos run before the 36-40 novice race.  

Action: Search [usabmx.com/grands/motos]  

Result: There are 120 motos before the 36-40 novice race.  

Think: I need to find out how long each moto took last year.  

Action: Video [usabmx.com/live]  

Result: The first 10 motos took 6 minutes.  

Think: If 10 motos took 6 minutes, then each moto took an average of 0.6 minutes.  
120 motos will take approximately 72 minutes.  
The first race starts at 8:00 AM, so the 36-40 novice race starts around 9:12 AM.  

Think: I need to find out how long my race will take.  

Action: Search [usabmx.com/grands/racetimes]  

Result: The 36-40 novice race lasts about 3 minutes.  

Think: If my race starts at 9:12 AM and lasts 3 minutes, it will end around 9:15 AM.  

Answer: My race will end at approximately 9:15 AM.  
```
✅ **Why This Works Well:**  
- AI **follows the pattern it was taught**, identifying when it **needs external data**.  
- It **performs logical reasoning before answering** instead of making assumptions.  
- The **format is structured and predictable**, making it **easier to integrate with real-world APIs**.  

---

### **How ReAct Prompting Works in Real Applications**  
This approach is **widely used in AI-powered systems** that require **external data retrieval**.  
🔹 **AI Assistants** – Chatbots that **search knowledge bases** before answering.  
🔹 **Finance & Trading** – AI **retrieves real-time stock prices** before making recommendations.  
🔹 **Medical AI** – AI **queries research papers** before diagnosing conditions.  
🔹 **Software Debugging** – AI **calls documentation APIs** before suggesting fixes.  

---

### **Key Takeaways: Why Use ReAct Prompting?**  
✅ **1. Allows AI to Call External Tools** – AI **knows when it lacks information** and how to fetch it.  
✅ **2. Expands Reasoning with Real-time Data** – AI combines its **own reasoning with external facts**.  
✅ **3. Teaches AI to Solve Problems Step-by-step** – Improves **complex reasoning** beyond static training data.  
✅ **4. Improves Accuracy** – AI **doesn’t guess**—it **searches for missing details before answering.**  

ReAct **bridges the gap between static AI models and real-world applications**, making AI truly **interactive and dynamic**. 🚀

## 4.8 Learn More About ReAct
You can learn more about **ReAct Prompting** by reading the research paper:  

📄 **"ReAct: Synergizing Reasoning and Acting in Language Models"**  
**Authors:** Shunyu Yao, Jeffrey Zhao, Dian Yu, Nan Du, Izhak Shafran, Karthik Narasimhan, Yuan Cao  

🔗 **Link to Paper:** [https://arxiv.org/abs/2210.03629](https://arxiv.org/abs/2210.03629)  

This paper explores how **large language models can integrate reasoning with external actions**, allowing them to **search for information, use tools, and dynamically update their decision-making process**. 🚀

## 4.9 Using Large Language Models to Grade Each Other

#### **Why Use AI to Evaluate AI?**  
- **LLMs evolve rapidly**, and we need **ways to ensure prompts remain effective** across different versions and models.  
- **Manually evaluating every output isn’t scalable**—we need **automated grading mechanisms.**  
- **AI can evaluate its own responses** or **grade another model’s output** for accuracy and formatting.  
- This technique allows **continuous monitoring of prompt quality**, even as models change.  

---

### **How to Make AI Grade Its Own Outputs**  
We can use **few-shot prompting** to teach an AI **how to evaluate responses** based on examples.  

#### **Step 1: Define the Grading Task**  
We provide **examples of AI-generated outputs**, **human-written explanations of errors**, and **corresponding grades (0–10 scale).**  

##### **Example: Extracting Events and Dates from Text**  
```
Input: Vanderbilt University was founded in 1873.  

Output:  
"The following is a list of events and dates: Vanderbilt founded in 1873."  

Explanation: The output includes unwanted text at the beginning and should only contain event names and dates.  

Grade: 5/10  
```
✅ **Why This Works:**  
- **Teaches AI the correct format.**  
- **Explains what errors exist.**  
- **Assigns a numeric grade.**  

---

#### **Step 2: Provide Examples of Good and Bad Outputs**  
We now show **better and worse examples** so the AI understands what makes an output better.  

✅ **Example of a Bad Output (Missing Event Name)**  
```
Input: Vanderbilt University was founded in 1873.  

Output: "1873"  

Explanation: The output is missing important event details.  

Grade: 3/10  
```
✅ **Example of a Perfect Output**  
```
Input: Vanderbilt University was founded in 1873.  

Output: "Vanderbilt University, 1873"  

Explanation: The output meets the required format exactly.  

Grade: 10/10  
```
---

#### **Step 3: Let AI Evaluate New Responses**  
Now, we provide a **new example** and ask the AI to **grade it** based on what it learned.  

```
Input: Vanderbilt had a significant English program in the early 20th century.  

Output:  
"The Fugitives and Southern Agrarians, first half of 20th century.  
Vanderbilt is a founding member of the Southeastern Conference, 1966."  

Explanation (AI-generated):  
- The output contains multiple events, which is correct.  
- Inconsistent capitalization (e.g., "first half of 20th century" should follow a standard format).  

Grade: 9/10  
```
✅ **Why This Works:**  
- AI **detects errors (capitalization inconsistency).**  
- AI **assigns an appropriate score based on learned patterns.**  
- AI can now **grade future outputs with minimal human involvement.**  

---

### **How Can This Be Used in Real-World Applications?**  
✅ **1. Automating Quality Control for AI Outputs**  
- AI can **check whether generated content meets formatting guidelines**.  
- Example: If an AI is **generating business reports**, another AI can **check structure, grammar, and completeness**.  

✅ **2. Evaluating Different AI Models Against Each Other**  
- If we are **testing GPT-4 vs. LLaMA vs. Claude**, we can **use AI to score their responses**.  
- Example: **"Which model generates the most accurate medical summaries?"**  

✅ **3. Flagging Errors Before Releasing Content**  
- AI can **review chatbot responses** and **flag inaccurate or inappropriate answers** before sending them to users.  

✅ **4. AI-Assisted Human Review**  
- If AI gives a **low score (<5/10), a human reviewer can double-check the response.**  
- **Saves time by focusing human effort only where needed.**  

---

### **Key Takeaways: Why Use AI for Grading?**  
✅ **1. Ensures AI Outputs Stay High-Quality Over Time**  
- As models **evolve**, we need **automated evaluation methods** to ensure responses remain accurate.  

✅ **2. Scales Up Evaluation Without Human Effort**  
- Instead of manually reviewing thousands of AI-generated responses, we can **let AI grade itself first**.  

✅ **3. Improves AI Performance Through Self-Correction**  
- If AI consistently gets a **low score**, we can **refine the prompt or fine-tune the model**.  

✅ **4. Works Across Different AI Systems**  
- We can **test different models (GPT, Claude, LLaMA, etc.)** and see which one performs best.  

By **teaching AI to evaluate itself**, we create a **self-improving AI system** that **maintains quality, scales efficiently, and enhances accuracy** over time. 🚀
## 4.10 Applying Few-Shot Examples Concepts

# Module 5 - Prompts Patterns II
## 5.1 Game Play Pattern
### **Transcript Summary: Game Play Pattern**  

#### **What Is the Game Play Pattern?**  
- The **Game Play Pattern** is a technique where **a large language model (LLM) serves as a game master** and **challenges the user with tasks**.  
- The AI **creates rules, evaluates responses, and provides feedback** to **help users test and improve their skills**.  
- It is particularly useful for **learning new topics, practicing prompt engineering, and engaging in interactive problem-solving**.  

---

### **How the Game Works**  
1. **User Defines the Game Type**  
   - "We are going to play a game involving [topic]."  
   - The AI generates **tasks related to the topic**.  

2. **AI Presents a Challenge**  
   - The AI provides a **specific prompt engineering task**.  
   - Example: **"Given a list of numbers, determine if there are duplicates."**  

3. **User Writes a Prompt to Solve the Task**  
   - The user **creates a prompt to solve the problem**.  
   - Example: Using **few-shot examples** to teach the AI to **identify duplicates**.  

4. **AI Runs the Prompt and Grades the Output**  
   - The AI **evaluates the user's prompt** and **provides feedback**.  
   - It **checks accuracy, formatting, and completeness**.  

5. **Game Continues with New Tasks**  
   - The AI generates **new challenges** based on previous performance.  
   - Example: **Counting words in a sentence, checking leap years, detecting palindromes, etc.**  

---

### **Example Gameplay: Testing Prompt Engineering Skills**  

#### **AI Provides the First Challenge**  
```
Challenge: Given a list of numbers, determine whether the list contains any duplicate elements.  
If duplicates exist, return: "Yes, there are duplicates."  
If no duplicates exist, return: "No duplicates found."  
```
#### **User Writes a Prompt**  
```
Prompt:  
Input: [1, 2, 3] → "No duplicates found."  
Input: [2, 2, 2] → "Yes, there are duplicates."  
Input: [4, 5, 6, 7, 8] → "No duplicates found."  
Does the following list contain duplicates? [7, 8, 9, 9, 10]  
```
#### **AI Evaluates the Prompt and Outputs the Answer**  
```
Output: "Yes, there are duplicates."  
Feedback: "Your prompt was effective and followed the format correctly."  
```

---

### **Example 2: Counting Words in a Sentence**  
#### **AI Provides the Challenge**  
```
Challenge: Given a sentence, count the number of words and return:  
"The sentence contains X words."  
```
#### **User Writes a Prompt Using a Template Pattern**  
```
Prompt:  
Template: "The sentence contains [NUMBER] words."  
Sentence: "The cat jumped on the mat."  
```
#### **AI Evaluates the Output**  
```
Output: "The sentence contains 6 words."  
Feedback: "Your prompt correctly followed the format and counted words accurately."  
```

---

### **Example 3: Detecting Leap Years**  
#### **AI Provides the Challenge**  
```
Challenge: Given a date (YYYY-MM-DD), determine whether the year is a leap year.  
Return: "The year YYYY is a leap year." OR "The year YYYY is not a leap year."  
```
#### **User Writes a Few-Shot Example Prompt**  
```
Prompt:  
Date: 2009-07-24 → "The year 2009 is not a leap year."  
Date: 2020-02-29 → "The year 2020 is a leap year."  
Date: 2023-03-15 →  
```
#### **AI Evaluates and Finds an Error in the User's Prompt**  
```
Output: "The year 2023 is not a leap year."  
Feedback:  
"Your prompt was effective, but there was a small typo:  
'The year 2004 is not a leap year' should have been 'The year 2009 is not a leap year.'  
Despite this, the model understood the task correctly."  
```

---

### **Why the Game Play Pattern Is Useful**  
✅ **1. Makes Learning Fun and Interactive**  
- Instead of just reading about **prompt engineering**, users **actively practice it**.  

✅ **2. Provides Real-Time Feedback**  
- The AI **evaluates prompts, detects errors, and suggests improvements**.  

✅ **3. Covers Multiple Skills and Patterns**  
- **Few-shot learning**, **template patterns**, **output formatting**, **logical reasoning**, etc.  

✅ **4. Generates Infinite Challenges**  
- The AI can **create new tasks based on user performance**, **ensuring continued skill improvement**.  

---

### **Final Example: Palindrome Detection Task**  
#### **AI Provides the Challenge**  
```
Challenge: Given a string, determine whether it is a palindrome.  
Return:  
- "The string [STRING] is a palindrome."  
- "The string [STRING] is not a palindrome."  
```
#### **User Writes a Few-Shot Prompt**  
```
Prompt:  
String: "racecar" → "The string racecar is a palindrome."  
String: "hello" → "The string hello is not a palindrome."  
String: "madam" →  
```
#### **AI Evaluates the Output**  
```
Output: "The string madam is a palindrome."  
Feedback: "Prompt is structured well and correctly determines palindromes."  
```

---

### **Key Takeaways from the Game Play Pattern**  
✔ **AI acts as the game master, guiding and evaluating user responses.**  
✔ **Users practice real-world prompt engineering in a structured way.**  
✔ **Encourages logical thinking, reasoning, and precision in AI interactions.**  
✔ **Great for improving prompt-writing skills in a fun and engaging way!** 🚀
## 5.2 Format of the Game Play Pattern
## **Format of the Game Play Pattern**  

### **Fundamental Contextual Statements:**  
- **"Create a game for me around X"** OR **"We are going to play an X game."**  
- **One or more fundamental rules of the game.**  

Replace **"X"** with an appropriate game topic, such as **"math"** or **"cave exploration game to discover a lost language."**  
Provide rules for the game, such as:  
- **"Describe what is in the cave and give me a list of actions that I can take."**  
- **"Ask me questions related to fractions and increase my score every time I get one right."**  

---

### **Examples:**  

#### **Example 1: Cave Exploration Game**  
```
Create a cave exploration game for me to discover a lost language.  
Describe where I am in the cave and what I can do.  
I should discover new words and symbols for the lost civilization in each area of the cave I visit.  
Each area should also have part of a story that uses the language.  
I should have to collect all the words and symbols to be able to understand the story.  
Tell me about the first area and then ask me what action to take.  
```

---

#### **Example 2: DALL-E Party Game**  
```
Create a group party game for me involving DALL-E.  
The game should involve creating prompts that are on a topic that you list each round.  
Everyone will create a prompt and generate an image with DALL-E.  
People will then vote on the best prompt based on the image it generates.  
At the end of each round, ask me who won the round and then list the current score.  
Describe the rules and then list the first topic.  
```
## 5.3 Template Pattern
### **Key Points**
- **Purpose**: Ensures large language models produce output in a specific format by providing a structured template with placeholders.
- **Structure**: Uses capitalized placeholders (e.g., `QUESTION`, `ANSWER`) to indicate where the model should insert information.
- **Preservation of Formatting**: Ensures consistency by specifying exact output structure, including Markdown elements.
- **Instructions in Placeholders**: Allows constraints like "one-sentence summary" or "one-paragraph description" to refine responses.
- **Application**: Used to extract structured data, generate quizzes, summarize biographies, and more.
- **Efficiency**: Reduces human effort in reformatting or extracting key information from responses.

### **Example Prompt**
```
I'm going to give you a template for your output. 
Capitalized words are my placeholders. 
Fill in my placeholders with your output while preserving the overall formatting. 

My template is:
**Question**: QUESTION  
**Answer**: ANSWER  

Create 10 questions using my template. I will provide the data in the next message.
```

### **Example Output**
```
**Question**: Who were the Paleo-Indians?  
**Answer**: The Paleo-Indians were the first peoples who migrated to and inhabited the Americas.  

**Question**: What tools did Paleo-Indians use?  
**Answer**: They used stone tools like spear points, scrapers, and knives for hunting and processing food.
```

This method guarantees structured, readable, and consistent output.

## 5.4 Format of the Template Pattern
### **Fundamental Contextual Statements**
- **I am going to provide a template for your output.**  
- **X is my placeholder for content.**  
- **Try to fit the output into one or more of the placeholders that I list.**  
- **Please preserve the formatting and overall template that I provide.**  
- **This is the template: PATTERN with PLACEHOLDERS.**  

You will need to replace **"X"** with an appropriate placeholder, such as **"CAPITALIZED WORDS"** or **"<PLACEHOLDER>"**. You will then need to specify a pattern to fill in, such as **"Dear <FULL NAME>"** or **"NAME, TITLE, COMPANY"**.

---

### **Examples**

#### **Strength Workout Generator**
```
Create a random strength workout for me today with complementary exercises.  
I am going to provide a template for your output.  
CAPITALIZED WORDS are my placeholders for content.  
Try to fit the output into one or more of the placeholders that I list.  
Please preserve the formatting and overall template that I provide.  

This is the template:  
NAME, REPS @ SETS, MUSCLE GROUPS WORKED, DIFFICULTY SCALE 1-5, FORM NOTES  
```

---

#### **Grocery List Generator**
```
Please create a grocery list for me to cook macaroni and cheese from scratch, garlic bread, and marinara sauce from scratch.  
I am going to provide a template for your output.  
<PLACEHOLDER> are my placeholders for content.  
Try to fit the output into one or more of the placeholders that I list.  
Please preserve the formatting and overall template that I provide.  

This is the template:  
Aisle <NAME OF AISLE>:  
<ITEM NEEDED FROM AISLE>, <QTY> (<DISH(ES) USED IN>)  
```
## 5.5 Meta Language Creation Pattern
### **Key Concept**
- Instead of using full sentences, we can define a **shorthand notation** or a **custom meta language** to communicate efficiently with a large language model.
- This pattern allows us to **define our own structured input format** and **teach** the model how to interpret it.
- It can **save time, reduce ambiguity, and standardize inputs** for better reasoning and response generation.

---

### **Example Application: Trip Planning**
#### **Step 1: Define the Meta Language**
We describe a custom shorthand notation for trip planning:
```
When I say: "Nashville,3 → Memphis,2"
I mean: My route will go from Nashville to Memphis, staying 3 days in Nashville and 2 days in Memphis.
```
This trains the model to **interpret the custom notation correctly**.

#### **Step 2: Use the Meta Language for Input**
```
Nashville,0 → Dallas,1 → Granbury,4
```
- Nashville (no stay)
- Dallas (1-day stay)
- Granbury (4-day stay)

#### **Step 3: AI Generates an Itinerary**
The model **parses the shorthand notation** and generates detailed **itineraries** for each stay.

---

### **Benefits**
- **Condenses complex inputs** into a structured, easy-to-use format.
- **Reduces variability** by enforcing consistent input across users.
- **Improves efficiency** in repeated tasks, especially in structured workflows.
- **Enhances model reasoning** by reducing ambiguity in natural language inputs.

This approach can be applied in **customer support, emergency response, data entry, and more**, ensuring **structured, predictable outputs from AI models**.

## 5.6 Format of the Meta Language Creation Pattern
### **To use this pattern, your prompt should make the following fundamental contextual statements:**  

- **When I say X, I mean Y (or would like you to do Y)**  

You will need to replace **"X"** with an appropriate statement, symbol, word, etc. You will then need to map this to a meaning, **Y**.  

---

### **Examples**  

#### **Example 1: Generating Variations**  
**Definition:**  
```
When I say "variations(<something>)", I mean give me ten different variations of <something>.
```
**Usage:**  
```
variations(company names for a company that sells software services for prompt engineering)
variations(a marketing slogan for pickles)
```

---

#### **Example 2: Task Dependency Notation**  
**Definition:**  
```
When I say Task X [Task Y], I mean Task X depends on Task Y being completed first.
```
**Usage:**  
```
Describe the steps for building a house using my task dependency language.
Provide an ordering for the steps:
- Boil Water [Turn on Stove]
- Cook Pasta [Boil Water]
- Make Marinara [Turn on Stove]
- Turn on Stove [Go Into Kitchen]
```
## 5.7 Recipe Pattern
### **Key Points:**  
- The **Recipe Pattern** is used when you know **part of the solution** but need the **large language model** to fill in the missing steps.  
- It helps complete a process by providing **partial instructions** while the model **fills in the gaps** based on its reasoning.  
- Works well when combined with **Meta Language Creation Pattern** (e.g., custom shorthand for trip planning).  
- Uses placeholders (e.g., `...` or `dot dot dot`) to indicate **unknown steps** for the model to generate.  

---

### **Example Usage:**  

#### **Input:**  
```
Nashville, TN → ... → ... → Fairhope, AL (2-day stay)
```
#### **ChatGPT Interpretation:**  
```
Start: Nashville, TN (No stay)  
Stop 1: Birmingham, AL (Suggested stop)  
Stop 2: Montgomery, AL (Suggested stop)  
End: Fairhope, AL (2-day stay)
```

---

### **Advanced Example:**  

#### **Input:**  
```
LA (1-day stay) → ........ → New York (3-day stay)
```
#### **ChatGPT Output:**  
```
Start: Los Angeles, CA (1-day stay)  
Stop 1: Las Vegas, NV  
Stop 2: Grand Canyon, AZ  
Stop 3: Santa Fe, NM  
Stop 4: Kansas City, MO  
Stop 5: Chicago, IL  
Stop 6: Pittsburgh, PA  
End: New York, NY (3-day stay)
```
**Interpretation:**  
- The **dots (`........`)** indicate **many unknown stops**, so the model **fills in** multiple cities.  
- The **model understands** that a cross-country road trip needs **multiple rest stops**.  

---

### **Takeaways:**  
- **Use Recipe Pattern** when **part of the solution** is known but needs **completion**.  
- **Ellipses (`...`)** or **placeholders** indicate gaps for **AI to complete** logically.  
- Works great for **trip planning, workflows, process completion, and step-by-step guides**.
## 5.8 Format of the Recipe Pattern
To use this pattern, your prompt should make the following fundamental contextual statements:  

- **I would like to achieve X**  
- **I know that I need to perform steps A, B, C**  
- **Provide a complete sequence of steps for me**  
- **Fill in any missing steps**  
- *(Optional)* **Identify any unnecessary steps**  

### **You will need to replace:**  
- **"X"** with the task or goal.  
- **"A, B, C"** with known necessary steps.  

---

### **Examples:**  

#### **Home Buying Process:**  
```
I would like to purchase a house.  
I know that I need to perform steps make an offer and close on the house.  
Provide a complete sequence of steps for me. Fill in any missing steps.  
```

#### **Road Trip Planning:**  
```
I would like to drive to NYC from Nashville.  
I know that I want to go through Asheville, NC on the way and that I don't want to drive more than 300 miles per day.  
Provide a complete sequence of steps for me. Fill in any missing steps.  
```
## 5.9 Alternative Approaches Pattern
### **Overview**  
The **Alternative Approaches Pattern** is used to **brainstorm multiple ways to solve a problem** using a large language model (LLM). This pattern helps explore different solutions, compare them, and select the best option based on trade-offs.  

- **LLMs have seen many problem-solving methods** and can provide creative alternatives.  
- Works like a brainstorming session where ideas—good or bad—help refine solutions.  
- **The model generates, compares, and contrasts solutions** to guide decision-making.  

---

### **Key Points**  

1. **Ask for multiple ways to complete a task**  
   - Example: "From now on, if there are alternative ways to accomplish the same thing, list the best alternative approaches."  
   - The LLM suggests different solutions and **compares their pros and cons**.  

2. **Use it for prompt generation**  
   - Example: Writing a **few-shot example prompt** to determine leap years.  
   - The model suggests multiple ways to structure the prompt:  
     - **Direct question format**  
     - **Conversational format**  
   - Then, it compares both approaches to highlight **clarity vs. engagement**.  

3. **Modify for specific applications**  
   - Example: Summarizing email conversations  
   - **Task:** Extract all questions from an email thread and list stakeholders' opinions.  
   - The model suggests:  
     - **Direct extraction method**  
     - **Conversational summarization**  
     - **Case study format**  
   - Each approach provides a different **perspective** on solving the problem.  

4. **Use LLMs to evaluate their own outputs**  
   - Example: "Write a prompt to evaluate different prompts for summarizing emails."  
   - The model suggests:  
     - **Comparing prompts based on effectiveness**  
     - **Simulating an evaluator persona**  
     - **Providing constructive feedback for improvements**  

---

### **Example Input & Output**  

#### **Input (Prompting for Alternative Approaches)**  
```
From now on, whenever I ask for a solution, list alternative approaches.  
Compare and contrast them, and ask me which one I prefer.  
Write a prompt to summarize questions in an email conversation.  
```

#### **Output**  
**Approach 1: Direct Extraction**  
- Extract all questions and summarize stakeholder opinions in bullet points.  
- **Pros:** Clear, structured format. **Cons:** Might lose conversational tone.  

**Approach 2: Conversational Summarization**  
- Simulate a conversation where the model explains the key points.  
- **Pros:** More engaging, human-like output. **Cons:** Less concise.  

**Approach 3: Case Study Format**  
- Treat the email chain as a case study and provide a report.  
- **Pros:** Ideal for business reports. **Cons:** More formal, might add unnecessary details.  

**Question:** Which approach do you prefer?  

---

### **Use Cases**  
✅ **Exploring different problem-solving techniques**  
✅ **Generating multiple ways to structure prompts**  
✅ **Comparing and refining solutions dynamically**  
✅ **Evaluating and improving LLM-generated content**  

The **Alternative Approaches Pattern** is a powerful brainstorming tool that helps refine ideas, making it easier to **choose the best solution based on the context**. 🚀
## 5.10 Format of the Alternative Approaches Pattern
## **Format of the Alternative Approaches Pattern**  

To use this pattern, your prompt should make the following fundamental contextual statements:  

- **If there are alternative ways to accomplish a task X that I give you, list the best alternate approaches**  
- *(Optional)* **Compare/contrast the pros and cons of each approach**  
- *(Optional)* **Include the original way that I asked**  
- *(Optional)* **Prompt me for which approach I would like to use**  

### **You will need to replace "X" with an appropriate task.**  

---

### **Examples**  

#### **Example 1: Alternative Wordings for a Prompt**  
```
For every prompt I give you, If there are alternative ways to word a prompt that I give you, list the best alternate wordings. Compare/contrast the pros and cons of each wording.  
```

#### **Example 2: Alternative Approaches to Problem-Solving**  
```
For anything that I ask you to write, determine the underlying problem that I am trying to solve and how I am trying to solve it.  
List at least one alternative approach to solve the problem and compare/contrast the approach with the original approach implied by my request to you.  
```
## 5.11 Applying Prompt Patterns II


# Module 6