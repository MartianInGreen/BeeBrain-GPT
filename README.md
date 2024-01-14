BeeBrain is an AutoAgent ReAct Framework that aims to significantly improve the performance of GPT-4 Turbo (especially within ChatGPT GPTs). 

It is heavily inspiered by [AutoExpert](https://github.com/spdustin/ChatGPT-AutoExpert?tab=readme-ov-file), and the [AutoExpert GPTs](https://chat.openai.com/g/g-LQHhJCXhW-autoexpert-chat) as well as the [ReAct Framework](https://react-lm.github.io/) for LLMs.

## Features

BeeBrain automatically assembles a panel of Experts for all topics, with prebuild experts for `Coding`, `Image (Generation)`, `Academic`, `Research`, `Writing`, `Science` and `Math`. BeeBrain self-prompts other Experts to enhance their follow up response. 

In addition BeeBrain has access to a variety of Tools (both default and new) to enhance it's capabilites significantly:
- Default ChatGPT Tools: DALLE-3 and Code Interpreter allow for generating Images and working with user files
- CodeRunner: Allows for the execution of code in rust, nodejs, c, cpp, csharp, go, bash, lua, and java. As well as an aditional python sandbox with network acess and the option to install additional python and system packages. 
- Searcher: An improvement of the default `Browsing` Tool. 
  - Search allows for search using the Brave Search API and the `perplexity-70b-online` llm.
  - PaperSearch allows for the search and access of scientific papers.
  - BrowsePage allows for the scraping and acessing of web pages.
- ImageGen: Acess to more (and more unrestricted) images models such as `SD-XL`, `Playground V2`, and `Open-Dalle`

## Usage 
You can follow the `Create-GPT.md` instructions to create your own custom GPT with this framework. Currently there is no Public GPT with this fully implemented availible due ot cost reasons. 