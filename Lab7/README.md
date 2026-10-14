# DAVE3625 - Lab7

<p align="center">
  <a href="https://github.com/DAVE3625/Dave3625-2026/tree/main/Lab7">
    <img src="img/header.png" alt="Working with Generative AI and Large Language Models" width="auto" height="auto">
  </a>
</p>

<p align="center">
  Working with Generative AI and Large Language Models<br>
  <br />
  ·
  <a href="https://github.com/DAVE3625/Dave3625-2026/issues">Report Bug</a>
  ·
  <a href="https://github.com/DAVE3625/Dave3625-2026/issues">Request Feature</a>
</p>

# Lab 7 - Working with Generative AI and Large Language Models (LLMs)

We will give short demos on how to use three different tools for working with LLMs: GitHub Copilot, Sikt KI, and ollama. These services are easy to use and have good documentation:


## GitHub Copilot:
- Allows you to connect an LLM to an agent, and work on larger filebases
- Requires a GitHub subscription (but a free education tier is available for OsloMet students)
- Takes some time to get approval
- https://github.com/education/students
- https://education.github.com/pack

## Ollama:
- Built on llama.cpp, allows local LLM inference, meaning you can download model weights and run the LLM on your own computer
- For more advanced models, you need high-end hardware (for example a GPU with dedicated VRAM)
- Smaller models can run on CPU and work fine for experimentation
- https://docs.ollama.com/

## Sikt KI:
- Chatbot service (similar to chatgpt.com or claude.ai)
- Freely available to OsloMet students (log in with Feide)
- User can choose between several models, including GPT-6, GPT-5.6 and Mistral Large 3
- https://ki.sikt.no/

## Others:
- Feel free to use any other chatbots you have access to for this lab.



# Exercises:

## Part 1 - Prompt experiments

The goal of this exercise is to make a LLM hallucinate. Try different prompts.

Some strategies:

- Ask the models for very recent or very obscure information

- Ask questions that don't make sense

- Ask questions with very little context

There are a number of ways to achieve this, feel free to google (or even ask an LLM) for more strategies.

*If you succeed in making the model hallucinate, try to change the prompt a little bit at a time until it no longer hallucinates an answer* (This might not always be possible)


## Part 2 - evaluate responses

1) Create some prompts you want to test the language models on. 10 prompts is a good start. Feel free to choose any topics you are interested in, and make a mix of easy and hard prompts.

2) Decide what you are looking for in a response for each prompt.

3) Run each prompt through each LLM, and save the output in a document

4) Evaluate each output against the criteria in 2) and assign a score from 0-10, but also note any interesting differences that you see after the fact. Did any of the models do anything unexpected? Any hallucinations?

5) Calculate the average score of each LLM. What do you think of the scores? Are there any changes you need to make to the prompts or criteria?

Optional reading - not curriculum: https://medium.com/online-inference/evaluating-large-language-models-llms-a-comprehensive-guide-for-practitioners-49e2ad345ac4

## Part 3 - reflection

1) How can we use what we have learned about hallucinations and evaluation of responses to create *better* prompts?

2) When *vibe coding*, what do we need to be wary about?

3) What makes the difference between a good and a bad prompt?

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.