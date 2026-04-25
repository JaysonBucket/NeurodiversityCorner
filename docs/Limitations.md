# ⚠️ Limitations


[← Back to Personalization](Personalization.md)  
[↑ Back to README](../README.md)

</br>

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
