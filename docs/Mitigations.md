# Mitigations

[← Back to Personalization](Personalization.md)  
[↑ Back to README](../README.md)

</br>

## 🔄 Reusing your personalization in agent sessions

Memory and Custom Instructions can make Copilot Chat much easier to work with.
However, they do **not automatically apply to Copilot agents**. Agent behaviour is controlled separately through agent instructions and configuration.
A practical workaround is to generate a short **session profile** from your existing preferences in Copilot Chat and then paste that profile into the agent at the start of a conversation.

<br>

- use this when your agent does not automatically reflect your personalization
- store the result to re-use as needed
- keep the block short
- update it occasionally if your preferred style changes

</br>

### Step 1: Generate a compact session profile in Copilot Chat

Use this prompt in normal Copilot Chat:

```
Based on the preferences you already apply for me in this chat, create a compact session profile I can manually reuse in agent conversations.

Your task:
- infer the most relevant active preferences from my usual interaction patterns
- focus on durable preferences only
- do not include temporary project details
- compress everything into a short, practical block
- prioritise the things that reduce friction most

Please structure the result into 4 sections:
1. Response style
2. Structure and formatting
3. Cognitive support needs
4. Things to avoid

Requirements:
- keep it concise
- use plain language
- make it suitable to paste at the start of an agent conversation
- avoid repetition
- prefer practical instructions over abstract descriptions

Then provide:
A. a compact bullet version
B. an ultra-short session starter version in one paragraph
```

</br>

### Step 2: Use it as conversation starter within the Agent interaction (Example, use your output from Step 1)
```
Before we begin, please use the following preferences for this conversation:

- Keep answers concise, structured and practical
- Start with the key point first
- Use bullet points instead of long paragraphs
- Use simple, direct language
- Give no more than 3 next steps at a time
- Summarise before going into detail
- Avoid overly polished or inflated wording
- Reduce cognitive load wherever possible
```

</br> 


