# AI in academic research

Workshop about using Large Language Models (LLMs) for research.

**Date and Time**: 24 April 2025, 1-4 pm.

**Location**: Psychology A16

**Requirements**: Please bring your laptop.

## Topics covered

- LLMs: privacy and data security.
- Current LLMs and their abilities and limitations.
- Tokenizers.
- Next-token prediction.
- Using local LLMs.
- Accessing LLMs through Apps and APIs.
- Word familiarity ratings from LLMs.
- Use LLMs to help with coding.
- Use LLMs to help with research.
- Providing context to LLMs: Model Context Protocol (MCP).
- The art of prompting.

## Activities

- [1 Try LLMs](/activities/activity1.md)
- [2 Tokenizer](/activities/activity2.md)
- [3 Next-token prediction](/activities/activity3.md)
- [4 Word familiarity ratings from LLM](/activities/activity4.md)
- [5 Using MCP servers with LLM](/activities/activity5.md)

Useful [Videos and readings](/background.md)

## Prepare your laptop for the workshop

<details>

<summary>Click to expand/collapse</summary>

Some useful software to install on your laptop before attending the workshop.

- [Witsy](https://witsyai.com)
- [LM Studio](https://lmstudio.ai)

You can also download Desktop clients of [ChatGPT](https://openai.com/chatgpt/download/) and [Claude](https://claude.ai/download).

### macOS

Install [brew](https://brew.sh). You might need to install Xcode Command Line Tools first. Enter the next line in the [Terminal](https://support.apple.com/en-gb/guide/terminal/welcome/mac):

```sh
xcode-select --install
```

Next install `Python` and `uv` using the [Terminal](https://support.apple.com/en-gb/guide/terminal/welcome/mac).

```sh
brew install python@3.12
brew install uv
```

### Windows

Install [scoop](https://scoop.sh).

Next install `Python` and `uv` using the [Windows Terminal](https://learn.microsoft.com/en-us/windows/terminal/).

```console
scoop bucket add versions
scoop install versions/python312
scoop bucket add main
scoop install main/uv
```

</details>
