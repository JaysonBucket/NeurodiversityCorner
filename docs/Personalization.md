# 🧠 Personalization
[↑ Back to README](../README.md)

## AI becomes significantly more helpful when it is adapted to how you work.
This is called **personalization**

<br>

In reality, using AI often comes with friction:

- answers are too long and difficult to scan  
- you have to repeatedly ask to simplify or shorten things  
- relevant information is buried and takes effort to extract  
- the tone feels too complex or “overly polished”  
- responses are not structured in a way that works for you  

<br>

Instead of fixing this every time manually, you can:

- reduce output complexity  
- define structure that works for you  
- establish consistent response patterns  
- remove unnecessary cognitive load  

<br>

Copilot offers two simple ways to do this:
- **[Copilot Memory](CopilotMemory.md)** → AI learns and adapts to your working patterns over time  
- **[Copilot Custom instructions](CopilotCustomInstructions.md)** → You define how AI should behave.

<br>


## When to use what

A simple rule of thumb:

- use **Memory** when something describes how you generally work  
- use **Custom Instructions** when you want AI to consistently respond in a specific way  

<br>

### Use Memory when...

- the pattern repeats  
- it reflects a personal preference or recurring challenge  
- you do not want to repeat it every time  

Examples:
- “I prefer short, structured answers”
- “I work best with checklist-style outputs”
- “I need tasks broken down into small steps”
- “I struggle more with finishing tasks than starting them”

<br>

### Use Custom Instructions when...

- you want a stable default format  
- you want less variation in responses  
- you already know what works well for you  

Examples:
- “Always use bullet points”
- “Keep answers concise”
- “Use simple, direct language”
- “Give me no more than 3 next steps at a time”

<br>

### Best practice

In many cases, the best setup is a combination of both:

- use **Memory** for your recurring personal patterns  
- use **Custom Instructions** for the response style and structure you want by default  

That way, AI becomes more useful without creating more work.

<br>

## Typical situations

You might recognise this:

- You get a long answer and don’t know where to start  
- You spend more time refining the output than using it  
- You constantly rephrase the same instructions  
- You need a specific format, but don’t get it by default  
- You feel the answer is “good” — but not usable  

The problem is not the AI.

> It is that the AI is not yet adapted to how you work.

<br>

## How to approach this

Start simple.

You do not need a perfect setup.

Instead:

- identify one recurring challenge  
- adjust AI slightly  
- see if it helps  
- keep what works  
- change what doesn’t  

<br>

## ⚠️ Limitations

Personalization can significantly reduce friction — but it has some important limitations.

<br>

### Scope

- **Memory and Custom Instructions are currently available in Copilot Chat experiences**
- They **do not apply to Copilot agents**
- Agent behaviour is controlled separately via agent instructions and configuration  

→ Source:
- [Microsoft Copilot Memory announcement](https://techcommunity.microsoft.com/blog/microsoft365copilotblog/introducing-copilot-memory-a-more-productive-and-personalized-ai-for-the-way-you/4432059) 

<br>

### Persistence and control

- Memory is stored per user and persists across sessions  
- It remains active until explicitly deleted  
- Custom Instructions also persist until changed or disabled  

→ Source:
- [Copilot personalization and memory (Microsoft Learn)](https://learn.microsoft.com/en-us/microsoft-365/copilot/copilot-personalization-memory) 

<br>

### Character and size limits

- Custom Instructions fields may have **practical character limits**  
- Microsoft does **not publish a single universal limit** for all Copilot surfaces  
- Limits can vary depending on product, mode, and UI  

<br>

### Behavioural limitations

- Memory only captures:
  - explicit user statements  
  - or patterns inferred from chat history  
- It does **not automatically understand everything about your workflow**  
- Custom Instructions do not guarantee perfect behaviour — responses may still need refinement  

→ Source:
- [Copilot personalization overview](https://nboldapp.com/microsoft-365-copilot-memory-custom-instructions-personalize-responses-safely/) 

<br>

### Agent considerations

- Copilot agents (Agent Builder / Copilot Studio) use:
  - their own instructions  
  - separate knowledge sources  
- Personal Memory and Custom Instructions from Chat are **not automatically reused**  

→ Source:
- [Agent Builder documentation](https://learn.microsoft.com/en-us/microsoft-365/copilot/extensibility/agent-builder) 

<br>

## Guiding idea

Personalization is powerful — but it is not global.

> It works best as a lightweight layer on top of Copilot Chat,  
> not as a universal configuration across all AI experiences.

Personalization is not about control.

It is about:

> making AI work in a way that reduces friction for you
