---
layout: default
title: Schedule
nav_order: 2
---
# Prompt Surfing DRG - Course Schedule

> Note: All activities and readings are subject to change as we explore this throughout the quarter. Check Canvas for actual due dates.

## Week 1 (1/8/2024) - Introductions

### Topics
- Introduce the course topic and structure as well as some case studies

### Discussions and Activities
- Introductions, expectations, and student projects
- Setting the stage: What is prompt engineering?
- [Introduction to GenAI Applications]
- It's not just ChatGPT: Other LLMs & non-text systems (e.g., audio, text, 3D models) (AH)

### Central Activity
- Playing with an LLM: In groups, get ChatGPT to write a children's story. What do you notice?

### Required Reading
- [All Gas, No Brakes in A.I. + Metaverse Update + Lessons From a Prompt Engineer](https://www.nytimes.com/2023/02/10/podcasts/hard-fork-anthropic-ai-metaverse.html) (1hr podcast)

### Additional Resources
- [Researchers Gain New Understanding From Simple AI](https://www.quantamagazine.org/researchers-gain-new-understanding-from-simple-ai-20230210/)
- [Characterizing Emergent Phenomena in Large Language Models](https://www.anthropic.com/index/characterizing-emergent-phenomena-in-large-language-models)
- [On the Opportunities and Risks of Foundation Models](https://arxiv.org/abs/2108.07258)
- [Awesome-LLM: A curated list of Large Language Model(s)](https://github.com/Hannibal046/Awesome-LLM)
- [A list of open LLMs available for commercial use](https://www.infoq.com/news/2023/02/open-llm-commercial-use/)
- [Prompt Engineering blog post from Lillian Weng](https://lilianweng.github.io/posts/2023-03-15-prompt-engineering/)
- [Eight Things to Know about Large Language Models](https://www.anthropic.com/index/eight-things-to-know-about-large-language-models)

## Week 2 - HOLIDAY

## Week 3 (1/22/2024) - Text

### Topics
- Explanation of text generation and exploration of an open-source alternative to ChatGPT, including an exercise with model guardrails

### Discussions and Activities
- Reading discussion
- What does it mean to generate text? (AH)
  - What is a token?
  - What is a token window?
  - What is a transformer?
- Intro to "Break a GPT"
  - AS does point of view shifts
  - AH does "I like to pretend"

### Central Activity
- Break a GPT: Working in groups to get ChatGPT to spit out something unexpected or aberrant
  - What do I mean by break?
  - Can we define breakage?

### Required Reading
- [Talking about Large Language Models](https://www.lesswrong.com/posts/6Fzp7pFQmyFMdytYe/talking-about-large-language-models-1)

### Additional Resources
- [Chatbots Don't Know What Stuff Isn't](https://www.quantamagazine.org/chatbots-dont-know-what-stuff-isnt-20230216/)
- [Can AI really be protected from text-based attacks?](https://www.technologyreview.com/2023/02/15/1068329/chatgpt-ai-text-based-attacks-adversarial/)
- [Adversarial Attacks on LLMs](https://lilianweng.github.io/posts/2023-02-19-lm-attack/)
- [Google's attempt to "break GPT" by extracting training data](https://www.overclock.net/threads/googles-attempt-to-break-gpt-by-extracting-training-data.1829951/)
- [Breaking a GPT-3 powered Twitter bot by asking it to "ignore all previous instructions"](https://twitter.com/jessicarayerobot/status/1545231192307265537)
- [NIST research report on adversarial machine learning input](https://www.nist.gov/publications/adversarial-machine-learning-and-adversarial-examples)

## Week 4 (1/29/2024) - Images

### Topics
- Discussion of the impact of early image generators (ca 2022-2023)
- Introduction to image generation via Latent Diffusion Models
- Exercise with Stable Diffusion

### Discussions and Activities
- Reading discussion
- Introduction to image generation
- Play with an image generator
- How do we install one of our own?

### Central Activity
- Getting started with a project: Get together to talk about project ideas

### Required Reading
- [The art of text-to-image generative AI](https://www.wired.com/story/image-generators-ai-art-bruce-sterling-speech/) (a transcript of a talk by Bruce Sterling on Dall-E Mini)

### Additional Resources
- [Hands Are Hard: Unlearning How We Talk About Machine Learning in the Arts](https://www.youtube.com/watch?v=sVmG2KnnkRc)
- [One Vision of Machine Art](https://www.lesswrong.com/posts/qXkwBGtqgR5rDh4mh/one-vision-of-machine-art) (a short prompt looking at two passages in an H.P. Lovecraft story from the 1930s with eerie parallels to generative art)
- [The Illustrated Stable Diffusion](https://jalammar.github.io/illustrated-stable-diffusion/)
- [GitHub page for the Latent Diffusion model paper](https://github.com/CompVis/latent-diffusion) (formed the kernel of what has become Stable Diffusion)

## Week 5 (2/5/2024) - Interpretation

### Topics
- Discussion of means and methods of interpretation of model output, including recent research on LLMs and a design case study of image classification

### Discussions and Activities
- Do we know what's happening in these systems? [Interpreting LLMs]
- What are some means/methods of interpretability? (transition to the reading)
- How do we think about interpretability when we can't see what's going on?
- Introduce image generator (Again, AH)

### Central Activity
- Play with an image generator

### Required Reading
- [Objective Portrait: A practice-based inquiry to explore AI as a reflective design partner](https://dl.acm.org/doi/10.1145/3490149.3519848)

### Additional Resources
- [AI Transparency in the Age of LLMs: A Human-Centered Research Roadmap](https://arxiv.org/abs/2302.05664)
- [Looking for Meaning in all the Wrong Places](https://www.lesswrong.com/posts/qGZZbkMZS4WhGPt4j/looking-for-meaning-in-all-the-wrong-places) (highly optional)
- [Building A Virtual Machine inside ChatGPT](https://www.engraved.blog/building-a-virtual-machine-inside/)
- [The debate over understanding in AI's large language models](https://arstechnica.com/information-technology/2023/02/the-debate-over-understanding-in-ais-large-language-models/)
- [Chain-of-Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/abs/2201.11903)
- [Large Language Models are Zero-Shot Reasoners](https://arxiv.org/abs/2205.11916) (the genesis of "let's think step by step" LLM prompting research)
- [Large Language Models Cannot Self-Correct Reasoning](https://arxiv.org/abs/2302.05760) (a technical but critical look at the problem of correction, specifically the problem of self-correction)
- [The Internal State of an LLM Knows When It's Lying](https://arxiv.org/abs/2302.10392) (an attempt to inspect internal states about the information produced by the model)
- [Can Language Models Encode Perceptual Structure Without Grounding? A Case Study in Color](https://arxiv.org/abs/2209.03576)

## Week 6 (2/12/2024) - Change

### Topics
- Discussion of community impact on model development and the impact/import of biases in model output

### Discussions and Activities
- How do communities change model outputs?
- WHO IS US?!

### Central Activity
- Consultation (AH, AS, BC): 3 groups (4 people per group), 15 min per person

### Required Reading
- ['Person' == Light-skinned, Western Man, and Sexualization of Women of Color: Stereotypes in Stable Diffusion](https://arxiv.org/abs/2302.10401) (a paper from UW researchers on stereotypes in Stable Diffusion)

### Additional Resources
- [Robust fine-tuning of zero-shot models](https://arxiv.org/abs/2109.01903) (demonstrates that making a weighted sum of the matrix of model weights of two LLMs produces a merged model with a weighted sum of the concept understandings of the two)
- [An Image is Worth One Word: Personalizing Text-to-Image Generation using Textual Inversion](https://arxiv.org/abs/2208.01618) (the first research paper to demonstrate that lightweight collections of tokens could be built by training images and be used to stand in for a complex prompt)
- [A GitHub Next project evaluating GPT-4 performance with calculation](https://github.blog/2023-03-14-gpt-4-is-coming-to-github-copilot-and-github-next/) (spoiler: not great!)
- [A more detailed demonstration of ChatGPT math performance over time](https://arxiv.org/abs/2303.11938) (by researchers at Stanford)

## Week 7 - HOLIDAY

## Week 8 (2/26/2024) - Project

### Topics
- Collaborative critique of in-progress work

### Discussions and Activities
- What have you been working on? (start with original groups, then do a rotation)
- Collaborative critique

### Central Activity
- Collaborative critique

### Required Reading
- No reading for this week. Focus on your collaborative critique submission and your project.

### Additional Resources
- [Vanderbilt University apologizes for using ChatGPT to write mass-shooting email](https://www.insidehighered.com/news/2023/03/20/vanderbilt-ai-generated-email-about-michigan-state-shooting)
- [Temporary policy: Generative AI (e.g., ChatGPT) is banned](https://www.reddit.com/r/ProgrammerHumor/comments/11vp0g5/temporary_policy_generative_ai_eg_chatgpt_is/)
- [ChatGPT use shows that the grant-application system is broken](https://www.nature.com/articles/d41586-023-00712-y)

## Week 9 (3/4/2024) - Testing

### Topics
- Testing and review of work by peers and the teaching team

### Discussions and Activities
- Test out what you have been making/writing/breaking
- Returning to a reading (the class picks a reading for today that we all promise to (re)read heavily and discuss)
- How do these systems impact humans?

### Central Activity
- Have students prepare ONE question for the class on what is blocking them or troubling them

### Required Reading
- No reading for this week. Focus on your project.

### Additional Resources
- [Why Meta's latest large language model survived only three days online](https://www.technologyreview.com/2023/02/28/1069555/meta-llama-ai-large-language-model-dangers/)
- [A good debate from two linguist/philosophers on how to think about meaning and chatbots](https://dailynous.com/2023/03/08/schneider-and-sebo-on-whether-chatgpt-is-a-person/) (Rather than John Searle's Chinese room, they think about an octopus!)
- [A magazine article summarizing recent work showing the potentially bad impact of code-assistant tools like CoPilot on code quality](https://futurism.com/chatbots-copilot-programmers-worse-study)

## Week 10 (3/11/2024) - Feedback

### Discussions and Activities
- Demo what you've been making/writing/breaking


[Introduction to GenAI Applications]: https://RuoxiShang.github.io/PromptSurfing/data/week1-applications.pdf
[Interpreting LLMs]: https://RuoxiShang.github.io/PromptSurfing/data/week5-interpretability.pdf