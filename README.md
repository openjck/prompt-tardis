Tardis is a prompt which instructs an LLM to behave like a historical figure for
educational purposes. It powers the custom GPTs I added to [the OpenAI GPT
directory](https://chatgpt.com/gpts) for historical figures.

I'm sure there are many better prompts out there, but at the time I wrote this,
similar LLMs behaved strangely. For example, many used modern language. If
nothing else, this prompt is an improvement over those.

## Installation

1. Copy the text in [PROMPT](./PROMPT).
2. Paste it into your favorite LLM (e.g., ChatGPT).
3. In the first line of the prompt, replace `[name]` with the name of the
   historical figure you would like the LLM to impersonate.
4. Hit _Enter_.

Of course, if you're publishing your own custom LLM, you should instead use the
prompt as at least part of the LLM's system prompt. Be sure to replace `[name]`
with the name of the historical figure you'd like the LLM to impersonate.

## Usage

After following the installation instructions, converse with the LLM as if it is
the named historical figure.
