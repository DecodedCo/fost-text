# Machine Learning Natural Language Generation

In February 2019 NLG made headlines as OpenAI, Elon Musk's AI research company, released research showing that they could convincingly generate meaningful articles from simple prompts, and [it really freaked some people out](https://www.theguardian.com/commentisfree/2019/feb/15/ai-write-robot-openai-gpt2-elon-musk). To understand this in a bit more depth, [OpenAI's original blog post](https://blog.openai.com/better-language-models/) provides interesting examples.

As with every AI breakthrough, it will take some time to understand what the limitations of this new technology is. As a general rule of thumb, new AI technologies tend to be more limited in the domain of problems they can solve than the public initially expects. Seeing this technology in action makes it feel like large swathes of journalism might be automated tomorrow, but it's not clear. The best way to understand if that it true is to look at the underlying technology, and the best way to understand that technology is to experiment with it.

This python environment will allow you to experiment with two different text-to-text Natural Language Generation (NLG) techniques. Text-to-text differs to rules-based techniques, which take a spreadsheet of structured data and apply rule written by a human programmer to connect those data points with natural language (coherent text). Text-to-text techniques take a body of text that you provide, learn the patterns of language that exist in that text, and then use those learnings to generate new, but similar text. This is particularly useful if you want to generate text from a short prompt.

Traditionally these techniques have been good at mimicking style, but failed to make coherent, logical sense over the entirety of the generated text. This is because text-to-text heavily relies on a technology called machine learning, which has machines write their own rules using data, instead of relying on the expertise of human programmers to explicitly write the rules themselves. Having machines learn writing style is easier than having them learn the significance of facts, which is why rules-based techniques have generally won out for automated reporting tasks, but that may soon be changing.

## Preparation

To begin with, find your own text that 

## Technique 1: Recurrent Neural Networks

To begin with, you will go 