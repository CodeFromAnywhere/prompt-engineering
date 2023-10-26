---
target-audience: LLM's that are used to create ActionSchema's
---

<!--

Content:

- It should summarize key concepts of prompt engineering that are required for quality of inference.
- It should provide concrete examples and the steps required to choose the right prompts.
- It should differentiate from other popular prompt engineering guides. They are very scientific and non practical, not easy to learn with
- It could have an added video course attached

-->

# A practical and interactive prompt engineering guide for Humans

Prompt engineering is a new science and practice that is all about the use of transformer AI in the best possible way. It comprises lots of different tools, techniques and practicalities. In this interactive guide I aim to make this new discipline approachable for any cognitive worker that wants to explore how this can have a positive impact in their career or within their business.

This guide does not go in-depth into the technical and scientific aspects, nor does it show you the inner workings of ML and Transformer AI models. Instead, my aim of this guide is to help you on your way to apply prompt engineering in your business and teach your fellow coworkers about the wonders of generative AI. That's why this guide will give you practical examples and applications of the different tools and techniques, and even makes it interactive, straight from the guide!

I hope this guide will serve you as a go-to place to look up useful tips, tricks, hacks, and tools. I hope you can use it to become to drastically enhance your efficiency and productivity in your carreer, whatever you do.

My name is Wijnand Karsens, and with a background in AI, App/web development and psychology, I have developed a tool called [ActionSchema](https://actionschema.com) that will help making this guide more interactive and compelling.

I hope you find it useful. Let's Start Prompting!

## Table of contents

**1. Introduction**

- **1.1** Models & Modalities
- **1.2** The Hottest Tools
- **1.3** Immersing yourself

**2. Prompt Techniques**

- Zero-shot prompts
- Few-shot prompts
- Chain of thought (CoT): https://www.promptingguide.ai/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fcot.1933d9fe.png&w=1920&q=75
- Zero-shot Chain of Thought (CoT): https://www.promptingguide.ai/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fzero-cot.79793bee.png&w=1920&q=75
- Self consistency: https://arxiv.org/abs/2203.11171
- Generate knowledge prompting: https://www.promptingguide.ai/techniques/knowledge
- Tree of thoughts: https://www.promptingguide.ai/techniques/tot
- Retreival Augmented Generation (RAG): https://www.promptingguide.ai/techniques/rag
- Active Prompt is CoT prompting where the examples are dynamic (https://www.promptingguide.ai/techniques/activeprompt)
- Tool-use, ReAct (Reason & Act), MRKL (Modular Reasoning, Knowledge and Language), PAL (Program-Aided Language Models): Let a LLM intermittently choose and use tools, get the result of it, and continue

**3. Prompt Chaining**

- Data Structurization
- Context Building
- Validation prompts
- Prompt with feedback loops
- Self Reflection

**4. Prompt Engineering in practice**

- Experimentation
- Cost tracking and reduction
- Hallicunation
- Context Length: Chunking, summarizing
- Quality & Consistency, Hallicunation: Context building
- Reliability: Feedback loops, validation prompts
- Privacy: legislation compliance, anonimisation

**5. Appendix**

- Other resources

## Introduction

Models & Modalities

- Text, Image and Audio omni-directional
- LMMs
- Choosing the right model

## Appendix

### Other resources

If you want to go deeper into the science, here are some awesome resources to learn more about prompt engineering.

- [Dair.ai Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide)
- [Brex's Prompt Engineering Guide](https://github.com/brexhq/prompt-engineering)
- [Trigaten's Learn Prompting](https://github.com/trigaten/Learn_Prompting)
- [OpenAI Cookbook](https://github.com/openai/openai-cookbook)
