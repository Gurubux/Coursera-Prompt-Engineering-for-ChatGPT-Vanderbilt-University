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