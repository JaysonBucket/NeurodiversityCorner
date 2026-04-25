## 🧠 Extracting Personalization from Past Conversations
[← Back to Personalization](Personalization.md)  
[↑ Back to README](../README.md)

</br>

Copilot can become significantly more helpful when it adapts to your individual preferences, thinking style, and recurring needs.
This section helps you extract those patterns from your past conversations and turn them into reusable customizations.


### 🎯 Goal

Identify:
- how you prefer answers to be structured
- which formats work best for you
- which recurring use cases you have
- which challenges you frequently face

Then convert this into:
- Memory entries (long-term personalization)
- Custom Instructions (behavioral defaults)
- Reusable prompts (portable context)


### 💬 Master Prompt: Extract Your Preferences

Use this prompt in Copilot Chat:
```
Analyze my recent conversations and identify recurring patterns in how I ask for responses to be adapted.


Your task:


1. Extract the most frequent adjustments I request (e.g. shorter answers, more structure, simpler language).
2. Identify the underlying needs behind these adjustments (e.g. reducing cognitive load, improving clarity, making outputs more usable).
3. Summarize how I generally communicate (style, level of detail, structure, iteration pattern).
4. Separate the findings into:
   - A) things that should be stored in Memory
   - B) things that should be defined as Custom Instructions


5. Provide two final outputs:
   OUTPUT 1:
   A single prompt I can use to update Copilot Memory with durable, recurring preferences.


   OUTPUT 2:
   A Custom Instructions suggestion that improves response quality immediately.


Keep everything concise, structured and practical.
```
</br>

### 🧩 Convert into Customization

**Option 1 — Memory (Best for long-term adaptation)**

Use for:
- stable preferences
- communication style
- recurring needs

Example (use your output of the Master Prompt):
```
Please remember how I prefer to work: I usually want concise-ready wording. I value clarity, completeness, and robust results, so please preserve important details and verify outputs rather than over-compressing them. Adapt tone and format to the audience and context. I often work in both German and English and prefer formal but friendly business English when writing in English. I also prefer clean Markdown formatting with clear headers and minimal visual clutter.```
```

</br>

**Option 2 — Custom Instructions (Best for behavior control)**

Use for:
- response style
- formatting defaults
- tone and structure

Example (use your output of the Master Prompt):
```
Respond in a concise, structured, and practical way. Start with. Prefer bullets, clear sections, and step-by-step guidance over long prose. Keep answers short by default unless I ask for more depth. Focus on actionable, reusable output such as ready-to-copy Markdown, prompts, templates, or presentation-ready text. Preserve important meaning and functionality when shortening or restructuring content. Prioritize clarity, completeness, and usability over decorative language. Use formal but friendly business English when writing in English, and adapt tone to the intended audience or use case.
```

</br>

**Option 3 — Session Prompt (Portable workaround)**

Use when:
- Memory/Instructions are not applied (e.g. agents)
- you want full control per session

Example ([see Mitigations page for further instructions](Mitigations.md)):
```
Use the following response style:
- concise
- structured with bullets
- actionable outputs only
- minimal explanation

Apply this consistently to all answers.
```

</br>

### 🔄 Iteration Loop (Recommended)

1. Run the extraction prompt
2. Add best results to Memory / Instructions
3. Test results in real usage
4. Refine periodically

Personalization improves over time.

</br>

### ✅ Key Principles

- Start simple, refine later
- Store only stable preferences in Memory
- Use Instructions for behavioral control
- Use prompts for maximum flexibility
