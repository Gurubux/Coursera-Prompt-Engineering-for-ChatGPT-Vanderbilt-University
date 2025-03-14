### Persona Pattern
Act as a -
### LLMs are not deterministic
### Training Data Cutoff - Outdated - Use Prompt to update with latest info
### Not Always Perfect
- First responses may contain errors. 
- Fine-tune prompts: Iteration is Key
### Determinism steps
If you want **strict determinism**, do the following:
1. **Set `temperature=0`, disable top-k and top-p sampling** (greedy decoding).
2. **Use a fixed random seed** (for local models) `torch.manual_seed(42) random.seed(42) np.random.seed(42)`.
3. **Avoid context history variability** (send only the latest prompt). 

## Control AI Behavior Through Prompts
### Using Prompts to Provide Missing Information
### LLMs retain contextual memory within a session
### AI operates on learned patterns—users must intentionally craft prompts to guide its behavior.
### Prompt engineering is about influencing output through word choice, structure, and context.
### The more refined and structured a prompt, the more precise the AI's response.
### Understanding pattern recognition helps in better structuring prompts for optimal AI performance.

## Programming-by-prompting
### Prompts function as dynamic programs, setting up structured behaviors.
### ChatGPT follows evolving instructions, allowing incremental refinement.
### Anyone can "program" ChatGPT by defining clear, structured, and layered instructions.
### Iterative interactions create complex, rule-based outputs, making AI a more effective tool.

##  Intro to Prompt Patterns
### Prompt patterns provide a structured way to guide LLM behavior.
### Since LLMs are trained on existing text patterns, structuring prompts in alignment with these patterns increases the likelihood of getting the desired response.
### Documenting and refining prompt patterns allows users to improve accuracy and reliability when working with LLMs.

## The Persona Pattern
### instructs an AI to adopt a specific role, perspective, or expertise.
### Ask to "act as" an expert, object, or character.
### Why Helpful
#### Condenses a lot of information into a short instruction
#### Adjusts tone, knowledge depth, and style dynamically.
#### Reduces prompt length
#### The persona pattern helps AI generate highly tailored responses by adopting roles.
#### Simple but information-dense

### Reading a Prompt Pattern
#### Different wordings can still follow the same pattern, as long as the fundamental contextual statements remain intact.
#### The “Helpful Assistant” pattern ensures AI maintains a positive, non-hostile tone.

### Format of the Persona Pattern
#### **Structure of the Persona Pattern**  
To effectively use the **Persona Pattern**, a prompt must include two **fundamental contextual statements**:  
1. **"Act as Persona X"** → Defines the AI’s role.  
2. **"Perform Task Y"** → Specifies the task the AI must complete.  

### New Information using Prompt
- Introducing new information via prompts allows AI to reason beyond its training limitations.
- Future AI applications will likely integrate retrieval mechanisms (e.g., databases, search engines) to gather and feed relevant documents into prompts dynamically.

### Prompt Size Limitations
- LLMs cannot process unlimited data in one prompt—users must optimize input length.
- Refining and condensing information is crucial for working within token constraints.

### Prompts are a Tool for Repeated Use
- Thinking of LLMs as one-shot tools is limiting—treat them as interactive problem-solving partners.
- **Refinement is key**: Each prompt builds upon previous ones to improve clarity, detail, and effectiveness.
- Prompting is not about getting a perfect answer on the first try—it’s about iterative refinement and exploration.

### Root Prompts
- Root prompts dictate core AI behaviors, setting boundaries and shaping responses.
- AI tools use root prompts to enforce ethical guidelines, prevent harmful content, and enhance usability.


## Question Refinement Pattern
- To use this pattern, your prompt should make the following fundamental contextual statements: 
```
From now on, whenever I ask a question, suggest a better version of the question to use instead. (Optional) Prompt me if I would like to use the better version instead.
```

## Cognitive Verifier Pattern
To use the Cognitive Verifier Pattern, your prompt should make the following fundamental contextual statements:
```	
	- When you are asked a question, follow these rules 
	- Generate a number of additional questions that would help more accurately answer the question 
	- Combine the answers to the individual questions to produce the final answer to the overall question
```


## Audience Persona Pattern
Assume I am...
```
Explain large language models to me. Assume I have no background in computer science.
Explain large language models to me. Assume I am Christopher Columbus.
Explain large language models to me. Assume I am a second grader who gets bored easily.
Explain large language models to me. Assume I only accept explanations in math.
```
```
Explain X to me. 
Assume that I am Persona Y.
```

## Flipped Interaction Pattern

```
- I would like you to ask me questions to achieve X 

- You should ask questions until condition Y is met or to achieve this goal (alternatively, forever) 

- (Optional) ask me the questions one at a time, two at a time, ask me the first question, etc.
```

## Few-shot Examples for Classification 
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
### Few-shot Examples for Actions/Decision Making

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
### Few-Shot Examples with Intermediate Steps
```
Situation: I'm traveling 60 miles per hour and I see the brake lights on the car in front of me come on.  
Action: Brake.  

```
- This directly maps an input (situation) to an output (single action).
- But real-world decisions require multiple steps.

Enhanced Example with Intermediate Steps:
```
Situation: I'm traveling 60 miles per hour and I see the brake lights on the car in front of me come on.  

Think: I need to slow the car down before I hit the car in front of me.  
Action: Press foot on brake.  

Think: The car isn't going to stop in time.  
Action: Check if the shoulder is wide enough to swerve into.  

Think: The shoulder is wide enough.  
Action: Swerve into the shoulder.  

```
- The AI now thinks through the steps needed to avoid an accident.
- Instead of one action, it evaluates options step-by-step before making decisions.

Another Example: Merging onto a Highway
```
Situation: I've just entered the highway from an on-ramp and I'm traveling at 30 miles per hour.  

Think: I need to speed up to the speed limit so that I don’t get hit from behind.  
Action: Press foot on accelerator.  

Think: I’ve reached the speed limit.  
Action: Let up on the accelerator.  

```
```
Situation: I'm backing out of a parking spot and I see the reverse lights illuminate on the car behind me.  

Action:  
```
#### AI Completes the Pattern:
```
Action: Immediately stop backing up.  

Think: I need to check my surroundings to make sure it's safe to continue backing up.  
Action: Check mirrors and surroundings for any obstacles or pedestrians.  

Think: It is safe to continue backing up.  
Action: Continue backing up slowly and carefully while keeping an eye on surroundings.  
```
- AI follows the example format, structuring decisions in a step-by-step process.
- Instead of stopping at a single action, it evaluates what to do next.


### Few-shot Prompting key points
1. Use Descriptive Prefixes
2. Provide Context Before Examples
3. Ensure Sufficient and Relevant Examples
4. Ensure AI Has Enough Data to Infer the Process
5. Choose Between Explicit Instructions vs. Learning by Example


## Chain of Thought Prompting
A prompting technique that improves AI reasoning by requiring it to "show its work."
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
✅ 1. Improves Accuracy: AI avoids mistakes by breaking complex tasks into logical steps.
✅ 2. Encourages Logical Flow: AI follows structured reasoning, making responses more reliable.
✅ 3. Helps Explainable AI (XAI): AI becomes more interpretable and transparent in decision-making.
✅ 4. Works for Various Domains: Useful for math, physics, logic puzzles, and complex decision-

## ReAct Prompting
Synergizing Reasoning and Acting in Language Models
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

## Using Large Language Models to Grade Each Other
In the Prompt give 
```
Input:
Output:
Explaination:
Grade: 5/10
```

Give Good and Bad exmaples
```
Input:
Output:
Explaination:
Grade: 2/10
Input:
Output:
Explaination:
Grade: 9/10
```

Then Give
Input and Output
And expect Grade with explaination 


## Game Play Pattern  

1️⃣ **AI Becomes the Game Master** – It creates the rules, challenges, and responses for an interactive game.  
2️⃣ **User Plays Along** – The AI presents tasks or questions, and the user responds (solving puzzles, answering questions, etc.).  
3️⃣ **AI Evaluates & Guides** – AI provides feedback, keeps score, or progresses the game based on user actions.  

---

### **Example: Trivia Game**  

#### **Input (User Starts the Game):**  
```
We are going to play a space exploration trivia game.  
Ask me space-related questions, keep track of my score, and increase it when I answer correctly.  
End the game when I say "stop" and tell me my final score.  
Ask me the first question.  
```

#### **Output (AI Responds with the First Question):**  
```
Welcome to the Space Exploration Trivia Game! 🚀  
I'll ask you questions about space, and you earn points for correct answers.  
Say "stop" when you want to end the game.  

Question 1:  
Which planet in our solar system has the most moons?  
A) Earth  
B) Jupiter  
C) Saturn  
D) Mars  

Your answer?  
```

## **Template Pattern**  
The **Template Pattern** helps structure the output of a large language model by defining placeholders within a predefined format. You specify a template with placeholders, and the model fills in the missing content while preserving formatting. This ensures consistency, especially when generating structured outputs like reports, summaries, or lists.  

**Example:**  
📌 **Prompt:**  
*"I am going to provide a template for your output. CAPITALIZED WORDS are placeholders. Fill in the placeholders while preserving the formatting. Here is the template:*  
- **Workout Name:** WORKOUT  
- **Muscle Group:** MUSCLE_GROUP  
- **Reps/Sets:** REPS_SETS  
- **Difficulty Level:** DIFFICULTY  

Create a strength training workout plan using this template."*  

📌 **Output:**  
- **Workout Name:** Deadlifts  
- **Muscle Group:** Lower Back & Hamstrings  
- **Reps/Sets:** 5 reps x 4 sets  
- **Difficulty Level:** 4/5  

---

## **Meta Language Creation Pattern**  
The **Meta Language Creation Pattern** allows you to define a shorthand or symbolic language to efficiently communicate with the model. You teach the model a new notation and provide its meaning, allowing for faster, more structured queries without lengthy explanations.  

**Example:**  
📌 **Prompt:**  
*"I am defining a meal planning shorthand. When I say 'Day X: Breakfast - Y, Lunch - Z, Dinner - A', I mean that on Day X, breakfast will be Y, lunch will be Z, and dinner will be A. Plan a 3-day meal plan using this format."*  

📌 **Output:**  
- **Day 1:** Breakfast - Oatmeal, Lunch - Grilled Chicken Salad, Dinner - Baked Salmon  
- **Day 2:** Breakfast - Scrambled Eggs, Lunch - Turkey Wrap, Dinner - Veggie Stir Fry  
- **Day 3:** Breakfast - Yogurt & Granola, Lunch - Avocado Toast, Dinner - Beef Stir Fry  

---

## **Recipe Pattern**  
The **Recipe Pattern** is used when you have partial knowledge of a process but need the model to fill in missing steps. You provide a goal and known steps, and the model completes the sequence logically, ensuring a well-structured outcome.  

**Example:**  
📌 **Prompt:**  
*"I would like to start a successful fitness coaching business. I know I need to create an online presence, develop workout plans, and engage with clients. Provide a complete sequence of steps, filling in any missing ones."*  

📌 **Output:**  
1. Choose a target audience (athletes, beginners, weight loss, etc.).  
2. Create a business brand, name, and logo.  
3. Develop a website and social media pages.  
4. Offer free workout plans to attract initial clients.  
5. Provide personalized coaching and track progress.  
6. Launch online courses or membership plans for recurring income.  

---

## **Alternative Approaches Pattern**  
The **Alternative Approaches Pattern** is used to brainstorm multiple ways to solve a problem. The model generates different methods, compares their pros and cons, and may prompt you to choose the best approach based on your needs.  

**Example:**  
📌 **Prompt:**  
*"I want to gain muscle effectively. List alternative approaches and compare them."*  

📌 **Output:**  
1. **Traditional Strength Training:** Uses progressive overload with heavy weights (Best for long-term muscle gains).  
2. **Calisthenics:** Bodyweight exercises like pull-ups and push-ups (Great for functional strength, but slower muscle growth).  
3. **High-Intensity Training (HIT):** Short, intense workouts with minimal rest (Good for quick sessions, but high fatigue).  

👉 *Which approach suits your lifestyle best?*  

