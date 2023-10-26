<!--

---
target-audience: LLM's that are used to create ActionSchema's
---

Content:

- It should summarize key concepts of prompt engineering that are required for quality of inference.
- It should provide concrete examples and the steps required to choose the right prompts.
- It should differentiate from other popular prompt engineering guides. They are very scientific and non practical, not easy to learn with
- It could have an added video course attached

Goal:

- Give myself a good overview of the different prompt engineering techniques I've found
- Document with instant value of top tips/tricks of prompt engineering to get leads on LinkedIn
- Ensure each prompt technique has a good example in a static table
- Update the static table so you can see the values nicely but also the plugins used become clear faster
- Turn this single document into many many social media stories.
- Use this as a foundation of AIGrunn presentation also.

-->

# A practical and interactive prompt engineering guide for Humans

## Table of contents

- [A practical and interactive prompt engineering guide for Humans](#a-practical-and-interactive-prompt-engineering-guide-for-humans)
  - [Table of contents](#table-of-contents)
- [1. Introduction](#1-introduction)
  - [1.1 Models \& Modalities](#11-models--modalities)
    - [The text realm](#the-text-realm)
    - [The image realm](#the-image-realm)
    - [The audio realm](#the-audio-realm)
  - [1.3 Hot tools \& Immersing yourself](#13-hot-tools--immersing-yourself)
- [2. Prompt Techniques](#2-prompt-techniques)
- [3. Prompt Chaining](#3-prompt-chaining)
- [4. Prompt Engineering in practice](#4-prompt-engineering-in-practice)
- [5. Agentic AI](#5-agentic-ai)
- [6. Appendix](#6-appendix)
  - [Other resources](#other-resources)

# 1. Introduction

Prompt engineering is a new science and practice that is all about the use of transformer AI in the best possible way. It comprises lots of different tools, techniques and practicalities. In this interactive guide I aim to make this new discipline approachable for any cognitive worker that wants to explore how this can have a positive impact in their career or within their business.

This guide does not go in-depth into the technical and scientific aspects, nor does it show you the inner workings of ML and Transformer AI models. Instead, my aim of this guide is to help you on your way to apply prompt engineering in your business and teach your fellow coworkers about the wonders of generative AI. That's why this guide will give you practical examples and applications of the different tools and techniques, and even makes it interactive, straight from the guide!

I hope this guide will serve you as a go-to place to look up useful tips, tricks, hacks, and tools. I hope you can use it to become to drastically enhance your efficiency and productivity in your carreer, whatever you do.

My name is Wijnand Karsens, and with a background in AI, App/web development and psychology, I have developed a tool called [ActionSchema](https://actionschema.com) that will help making this guide more interactive and compelling.

I hope you find it useful. Let's Start Prompting!

## 1.1 Models & Modalities

Prompt engineering is mostly meant for Generative Transformer Models that have become popular after the 2017 paper [Attention is all you need](https://arxiv.org/abs/1706.03762). Prompt engineering is the science of understanding a models capabilities, and using the model in the best possible way to get desired outcomes.

In this guide, we'll cover different techniques and different models in multiple modalities. The most important modality is the text-domain. Models like GPT-3.5 (ChatGPT) and GPT4 have become popular in the beginning of 2023. However, the same transformer models are also applied in the image and audio domain. This guide also covers image generation, image analysis, text to speech, and speech to text.

Here's an overview of what will be covered in this guide:

![Prompt engineering across modalities](./multi-modal-system.drawio.png)

### The text realm

The text realm is the most interesting realm for most people. It comprises all possible things you can do with text by predicting the next word. A couple things which this guide will cover are:

- Question answering
- Completion
- Chat
- Categorization
- Data Structurization

Popular models in the text realm include but aren't limited to:

- ChatGPT or GPT 3.5 turbo (OpenAI)
- GPT4 (OpenAI)
- LLaMa 2 (Meta)
- Claude 2 (Anthropic)
- Bard (Google)

### The image realm

In the image realm we can also transform things.

In this guide we'll cover:

- **Image Generation**: Models such as MidJourney, Stable Diffusion XL, and Dall-E 3 have gained recent popularity
- **Image Analysis**: A relatively new transformation that is gaining popularity: GPT4-V and LLaVa are currently the top of the line image analysers
- **Image Editing**: We can use text and image instructions to edit an entire image or part of it. OpenAI, StabilityAI, and MidJourney all have these type of models.

### The audio realm

In the audio realm, these are the different transformations we'll cover:

- **Text to Speech**
- **Transcription / Speech to text**:
- **Cleaning**: Audio can be cleaned or enhanced.

**Large Multimodal Models**

Recent papers mention the emergence of Large multimodal models, which are integrated models that integrate multiple modalities into a single model. ChatGPT has recently launched vision and voice capabilities into its product, and it's expected that this will become more common as it's very useful.

## 1.3 Hot tools & Immersing yourself

To learn about all the possibilities in the wonderful world of generative AI, I'd recommend to immerse yourself in a set of tools that help you across anything you do. There are many popular tools available, here are a few tips:

- [ChatGPT Plus](https://chat.openai.com) for conversations across major modalities
- [Numerous.ai](https://numerous.ai) for working with structured data in the text-domain
- [ActionSchema](https://actionschema.com) for working with structured data in any domain, and for making prompt chains

In this guide, we'll use the interactive ActionSchema playground to show different techniques.

# 2. Prompt Techniques

Coming soon. Topics:

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

For early access, see [my workshop](https://www.actionschema.com/about/workshop.md)

# 3. Prompt Chaining

Coming soon. Topics:

- Data Structurization
- Context Building
- Validation prompts
- Prompt with feedback loops
- Self Reflection

For early access, see [my workshop](https://www.actionschema.com/about/workshop.md)

# 4. Prompt Engineering in practice

Coming soon. Topics:

- Experimentation
- Cost tracking and reduction
- Hallicunation
- Context Length: Chunking, summarizing
- Quality & Consistency, Hallicunation: Context building
- Reliability: Feedback loops, validation prompts
- Privacy: legislation compliance, anonimisation

For early access, see [my workshop](https://www.actionschema.com/about/workshop.md)

# 5. Agentic AI

Coming soon. For early access, see [my workshop](https://www.actionschema.com/about/workshop.md)

Topics:

- Intro to AutoGPT-like Agents
- Landscape
- AI Safety

# 6. Appendix

## Other resources

If you want to go deeper into the science, here are some awesome resources to learn more about prompt engineering.

- [Dair.ai Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide)
- [Brex's Prompt Engineering Guide](https://github.com/brexhq/prompt-engineering)
- [Trigaten's Learn Prompting](https://github.com/trigaten/Learn_Prompting)
- [OpenAI Cookbook](https://github.com/openai/openai-cookbook)
