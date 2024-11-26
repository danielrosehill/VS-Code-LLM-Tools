# Prompt for populating these lists

## Foundational instruction

I'm gathering a list of VS Code extensions that have to do with prompt engineering and working with LLMs.

Here's an example of an extension that's interesting to me:

https://marketplace.visualstudio.com/items?itemName=HuggingFace.huggingface-vscode

To speed up the process, I'd like to establish the following workflow:

1: I'll populate a link into the chat, like:

https://marketplace.visualstudio.com/items?itemName=HuggingFace.huggingface-vscode

2: You will respond with exactly the following, enclosed within a markdown codeblock:

# Extension Name (Publisher Name)

(Shields.io install count badge)

Installation code for command pallette

1 line description

## For example

```
# [llm-vscode (Hugging Face)](https://marketplace.visualstudio.com/items?itemName=HuggingFace.huggingface-vscode)

![Visual Studio Marketplace](https://img.shields.io/visual-studio-marketplace/v/HuggingFace.huggingface-vscode?label=VS%20Code%20Marketplace&logo=visual-studio-code&style=for-the-badge)
![Installs](https://img.shields.io/visual-studio-marketplace/i/HuggingFace.huggingface-vscode?label=Installs&style=for-the-badge)
 
llm-vscode is an extension for all things LLM. It uses llm-ls as its backend.

Install code:
`ext install HuggingFace.huggingface-vscode`

```

 ---

 # Prompt as codeblock

 If you'd like to use this prompt for your own mapping project(s) and would prefer to copy it out of a codeblock:

 ## Plain text formatting

 You'll need to add back in the codefence delimeters (```)

 ```text
 I'm gathering a list of VS Code extensions that have to do with prompt engineering and working with LLMs.

Here's an example of an extension that's interesting to me:

https://marketplace.visualstudio.com/items?itemName=HuggingFace.huggingface-vscode

To speed up the process, I'd like to establish the following workflow:

1: I'll populate a link into the chat, like:

https://marketplace.visualstudio.com/items?itemName=HuggingFace.huggingface-vscode

2: You will respond with exactly the following, enclosed within a markdown codeblock:

# Extension Name (Publisher Name)

(Shields.io install count badge)

Installation code for command pallette

1 line description

## For example

# [llm-vscode (Hugging Face)](https://marketplace.visualstudio.com/items?itemName=HuggingFace.huggingface-vscode)

![Visual Studio Marketplace](https://img.shields.io/visual-studio-marketplace/v/HuggingFace.huggingface-vscode?label=VS%20Code%20Marketplace&logo=visual-studio-code&style=for-the-badge)
![Installs](https://img.shields.io/visual-studio-marketplace/i/HuggingFace.huggingface-vscode?label=Installs&style=for-the-badge)
 
llm-vscode is an extension for all things LLM. It uses llm-ls as its backend.

Install code:
`ext install HuggingFace.huggingface-vscode`


```

## Markdown

 ```markdown
 I'm gathering a list of VS Code extensions that have to do with prompt engineering and working with LLMs.

Here's an example of an extension that's interesting to me:

https://marketplace.visualstudio.com/items?itemName=HuggingFace.huggingface-vscode

To speed up the process, I'd like to establish the following workflow:

1: I'll populate a link into the chat, like:

https://marketplace.visualstudio.com/items?itemName=HuggingFace.huggingface-vscode

2: You will respond with exactly the following, enclosed within a markdown codeblock:

# Extension Name (Publisher Name)

(Shields.io install count badge)

Installation code for command pallette

1 line description

## For example

# [llm-vscode (Hugging Face)](https://marketplace.visualstudio.com/items?itemName=HuggingFace.huggingface-vscode)

![Visual Studio Marketplace](https://img.shields.io/visual-studio-marketplace/v/HuggingFace.huggingface-vscode?label=VS%20Code%20Marketplace&logo=visual-studio-code&style=for-the-badge)
![Installs](https://img.shields.io/visual-studio-marketplace/i/HuggingFace.huggingface-vscode?label=Installs&style=for-the-badge)
 
llm-vscode is an extension for all things LLM. It uses llm-ls as its backend.

Install code:
`ext install HuggingFace.huggingface-vscode`


```