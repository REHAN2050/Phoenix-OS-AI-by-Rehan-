# 🧩 Sample AI Agent

```python
# Sample pseudo agent structure
class AIAgent:
    def __init__(self, name):
        self.name = name
        self.knowledge = []

    def learn(self, input):
        self.knowledge.append(input)

    def respond(self, prompt):
        # Very basic logic
        return f"{self.name} says: {prompt.upper()}"

# Example
agent = AIAgent("Phoenix-GPT")
agent.learn("1+1=2")
print(agent.respond("hello"))
