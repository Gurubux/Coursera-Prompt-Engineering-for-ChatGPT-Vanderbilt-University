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