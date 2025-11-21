# ChatGPT Instructions Repository

A reusable set of custom instructions intended for use with ChatGPT or any other large-language model.  
The goal: provide a **clear, minimal**, copy-and-paste friendly instruction set that works well in any context or language.

---

## What’s inside

- **custom-instructions.txt** — the core instruction set.  
  Raw link: https://raw.githubusercontent.com/Xopoc/ChatGPT-instructions/main/custom-instructions.txt  
  You can copy the entire content directly into your model’s system prompt or Custom Instructions.

---

## Why use this

This instruction set is designed to produce consistent, reliable, and high-quality responses from any LLM.  
The rules are **language-agnostic** — they work the same way in any language, and you do not need to translate them.

**Key benefits:**

- Ensures clear separation between **facts**, **opinions**, and **uncertainty**.
- Encourages **best-practice**, future-oriented reasoning rather than shallow or generic responses.
- Uses web search when freshness matters and **cites factual claims** by default.
- Requests clarifying details instead of guessing or hallucinating.
- Gives structured reasoning:
  - pros/cons only when comparing,
  - scenarios only for forecasting.
- Keeps answers short and clear, but adds more detail if you ask for it or when it helps.
- Works with **any language input** and applies the same reasoning rules automatically.
- Designed to be easily copied into any LLM system prompt or custom instruction field.

---

## How to use

1. Open the raw file link above.  
2. Copy the full content of `custom-instructions.txt`.  
3. Paste into one of the following:
   - ChatGPT → **Settings → Custom Instructions**, or  
   - The **system/assistant** prompt in your own bot, agent, or API integration.
4. (Optional) Add your own personal or project-specific context as a separate section if needed.

No formatting changes or translation are required — the rules are plain text and language-independent.

---

## License

This project is licensed under the **MIT License** — you are free to copy, modify, use, and redistribute these instructions with minimal requirements (include the license text).

---

## Contributing

Contributions are welcome!

Feel free to open an issue or pull request if you want to:

- improve clarity or structure,  
- refine or suggest reasoning rules,  
- propose better general-purpose defaults.

---

## Acknowledgements

Thanks to everyone working on improving LLM reliability and prompt design.  
If this repository helps your workflows, feel free to share or reference it.
