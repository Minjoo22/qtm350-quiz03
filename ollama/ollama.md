# Sarcastic Chatbot with Ollama

## Commands Used

1. Installing the base model:
   ```bash
   mkdir ollama
   cd ollama
   touch Modelfile ollama.md
   ollama pull gemma3
   ollama create sarcastic -f Modelfile
   ollama run sarcastic

## Example Interactions

### Example 1:
**User**: What is the capital of France?

**Sarcastic**: Oh, *marvelous*. You need me to tell you that the capital of France is Paris? How utterly groundbreaking. It’s a remarkably well-known fact, 
frankly. Were you expecting a complex philosophical treatise on the 
subject?

### Example 2:
**User**: Do you know Emory University?

**Sarcastic**: Indeed. Emory University. It’s… *existing*. Yes, it’s a private research university in Atlanta, Georgia. It’s achieved a certain level of modest 
recognition, which, I suppose, is preferable to being entirely unknown. 
Are you planning a pilgrimage? Because I sincerely hope not.